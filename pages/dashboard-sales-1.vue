<template>
  <div class="bg-gray-400 h-screen p-4 flex flex-row text-gray-700">
    <div
      id="left-sidebar"
      class="h-full bg-gray-300 rounded-2xl flex flex-col p-4"
    >
      <div class="flex flex-col justify-between h-full items-center">
        <div class="space-y-3">
          <div id="logo">
            <Icon name="logos:100tb" size="3em" />
          </div>
          <hr class="my-8 h-px bg-gray-200 border-0 dark:bg-gray-700" />
          <div id="links" class="flex flex-col items-center space-y-8">
            <Icon name="logos:google" size="2em" />
            <Icon name="logos:facebook" size="2em" />
            <Icon name="logos:instagram-icon" size="2em" />
          </div>
        </div>
        <div id="settings">
          <Icon name="logos:twitter" size="2em" />
        </div>
      </div>
    </div>
    <div id="right-content" class="w-full px-4">
      <div
        id="header"
        class="flex flex-row justify-between items-center bg-gray-300 px-8 rounded-2xl"
      >
        <div class="text-2xl">Analytics Overview</div>
        <div class="flex flex-row space-x-8 items-center">
          <div class="flex flex-row items-center space-x-2">
            <div>
              <Icon name="material-symbols:calendar-month-outline" size="2em" />
            </div>
            <div class="flex flex-col">
              <div class="text-xl font-medium">12 May</div>
              <div class="text-xs font-medium text-gray-500">02:00 AM</div>
            </div>
          </div>
          <div class="relative">
            <Icon
              name="healthicons:magnifying-glass-outline"
              size="2em"
              class="absolute top-1/4 left-3"
            />
            <input
              type="text"
              placeholder="Search"
              class="rounded-2xl py-6 pl-14"
            />
          </div>
        </div>
        <div class="flex flex-row items-center space-x-8">
          <div
            id="lang"
            class="border-dashed border-2 border-gray-400 flex flex-row rounded-full"
          >
            <div class="py-1 px-3 bg-gray-100 rounded-full">
              EN
            </div>
            <div class="py-1 px-3">
              IN
            </div>
          </div>
          <div
            id="notifications"
            class="flex flex-row items-center space-x-4 border-2 border-gray-400 rounded-2xl py-2 px-4"
          >
            <div>
              <div class="text-sm">
                You have 2 new notifications
              </div>
              <div class="text-xs">
                View Inbox
              </div>
            </div>
            <div>
              <Icon name="bxs:bell" size="2em" />
            </div>
          </div>
          <div id="avatar">
            <img
              src="https://unsplash.com/photos/mEZ3PoFGs_k/download?ixid=MnwxMjA3fDB8MXxhbGx8fHx8fHx8Mnx8MTY3MTc0NDkyNA&force=true&w=1920"
              class="h-12 w-12 rounded-full object-cover object-top"
            />
          </div>
        </div>
      </div>
      <div id="content" class="mt-2 flex flex-row">
        <div id="main-content">
          <div
            id="financial-data"
            class="flex flex-row rounded-2xl bg-gray-300"
          >
            <div class="p-6">
              <div>
                <p class="text-xl">
                  Financial
                </p>
                <p class="text-xs text-gray-500">May 1, 2022 - Sep 1, 2022</p>
              </div>
              <div class="flex flex-row mt-4 justify-between">
                <div>
                  <p>
                    <Icon name="fa6-solid:circle-dot" />
                    <span class="ml-2">Total Sales</span>
                  </p>
                  <p class="ml-6">5,273</p>
                  <p class="ml-6">Products</p>
                </div>
                <div class="w-px bg-gray-400"></div>
                <div>
                  <p>
                    <Icon name="fa6-solid:circle-dot" />
                    <span class="ml-2">Total Views</span>
                  </p>
                  <p class="ml-6">42,725</p>
                  <p class="ml-6">Views</p>
                </div>
              </div>
              <div
                class="border-2 border-gray-400 rounded-2xl py-4 pl-4 pr-24 -ml-4 mt-4 space-y-2"
              >
                <p class="text-sm">
                  Total Revenue <span class="text-green-700">+ 10.27 %</span>
                </p>
                <p class="text-2xl font-bold">$ 31,147,13</p>
                <p class="text-sm text-gray-400">
                  Increased 15% from last month
                </p>
              </div>
            </div>
            <div class="bg-gray-200 rounded-2xl p-6">
              <div>
                <div class="text-xl">
                  Chronich Condition
                </div>
                <div>
                  Month arrow
                </div>
              </div>
              <div class="h-1/2">
                <img
                  src="https://unsplash.com/photos/l3N9Q27zULw/download?ixid=MnwxMjA3fDB8MXxzZWFyY2h8MzJ8fGNoYXJ0fGVufDB8fHx8MTY3MTgyODgzOQ&force=true&w=640"
                  alt=""
                  class="object-bottom"
                />
              </div>
            </div>
          </div>
          <div id="daily-activity-chart">
            Daily Activity Chart
          </div>
        </div>

        <div id="agent-rates">
          Rates
        </div>
      </div>
    </div>
  </div>
</template>
