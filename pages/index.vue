<script setup>
const route = useRouter()
const all_pages = ref([])

all_pages.value = route.options.routes
</script>

<template>
  <div>
    <client-only>
      <ol>
        <div
          v-for="page in all_pages.filter((obj) => obj.path !== '/')"
          :key="page.path"
        >
          <div class="title-route">
            <li>
              <NuxtLink :to="page.path">
                {{ page.name.replaceAll('-', ' ') }}
              </NuxtLink>
            </li>
          </div>
        </div>
      </ol>
    </client-only>
  </div>
</template>

<style scoped>
.title-route {
  text-transform: capitalize;
}
</style>
