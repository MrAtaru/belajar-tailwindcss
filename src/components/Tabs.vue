<template>
  <div class="mb-4 border-b border-gray-200 dark:border-gray-700">
    <ul
      class="hidden text-sm font-medium text-center text-gray-500 divide-x divide-gray-200 rounded-lg shadow sm:flex dark:divide-gray-700 dark:text-gray-400"
      id="myTab"
      data-tabs-toggle="#myTabContent"
      role="tablist"
    >
      <li class="w-full" role="presentation">
        <button
          class="inline-block w-full p-4 bg-white hover:text-gray-700 hover:bg-gray-50 dark:hover:text-white dark:bg-gray-800 dark:hover:bg-gray-700"
          id="profile-tab"
          data-tabs-target="#profile"
          type="button"
          role="tab"
          aria-controls="profile"
          aria-selected="false"
        >
          MBF-P02 Gundam Astray Red Frame
        </button>
      </li>
      <li class="w-full" role="presentation">
        <button
          class="inline-block w-full p-4 bg-white hover:text-gray-700 hover:bg-gray-50 dark:hover:text-white dark:bg-gray-800 dark:hover:bg-gray-700"
          id="dashboard-tab"
          data-tabs-target="#dashboard"
          type="button"
          role="tab"
          aria-controls="dashboard"
          aria-selected="false"
        >
          RX-0 Unicorn Gundam
        </button>
      </li>
      <li class="w-full" role="presentation">
        <button
          class="inline-block w-full p-4 bg-white hover:text-gray-700 hover:bg-gray-50 dark:hover:text-white dark:bg-gray-800 dark:hover:bg-gray-700"
          id="settings-tab"
          data-tabs-target="#settings"
          type="button"
          role="tab"
          aria-controls="settings"
          aria-selected="false"
        >
          ZGMF-X20A Strike Freedom Gundam
        </button>
      </li>
    </ul>
  </div>
  <div id="myTabContent">
    <div class="hidden p-4 rounded-lg bg-gray-50 dark:bg-gray-800" id="profile" role="tabpanel" aria-labelledby="profile-tab">
      <div class="grid-cols-2 md:grid-cols-3 gap-4">
        <div>
          <div class="grid md:grid-cols-2 gap-8">
            <div class="bg-gray-50 dark:bg-gray-800 border border-gray-200 dark:border-gray-700 rounded-lg p-8 md:p-12">
              <h2 class="text-gray-900 text-center dark:text-white text-3xl font-extrabold mb-2">
                MBF-P02 Gundam Astray Red Frame
              </h2>
              <hr class="h-px my-8 bg-gray-200 border-0 dark:bg-gray-700" />
              <p class="text-lg font-normal text-gray-500 dark:text-gray-400 mb-4">
                The MBF-P02 Gundam Astray Red Frame is a Mobile Suit introduced in the manga Mobile Suit Gundam SEED Astray. It is
                piloted by Junk Guild member Lowe Guele. <br /><br />
                The MBF-P02 Gundam Astray Red Frame is one of five identical prototype mobile suits developed by Orb using stolen
                data from the Earth Alliance's G Project.
              </p>
              <a
                href="https://gundam.fandom.com/wiki/MBF-P02_Gundam_Astray_Red_Frame"
                class="text-blue-600 dark:text-blue-500 hover:underline font-medium text-lg inline-flex items-center"
                >Read more
                <svg
                  class="w-3.5 h-3.5 ml-2"
                  aria-hidden="true"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 14 10"
                >
                  <path
                    stroke="currentColor"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M1 5h12m0 0L9 1m4 4L9 9"
                  />
                </svg>
              </a>
            </div>
            <div class="bg-gray-50 dark:bg-gray-800 border border-gray-200 dark:border-gray-700 rounded-lg p-8 md:p-12">
              <div id="custom-controls-gallery" class="relative w-full" data-carousel="slide">
                <!-- Carousel wrapper -->
                <div class="relative h-56 overflow-hidden rounded-lg md:h-96">
                  <!-- Item 1 -->
                  <div class="hidden duration-700 ease-in-out" data-carousel-item="active">
                    <img
                      src="/Mbf-p02d.jpg"
                      class="shadow-xl dark:shadow-gray-800 rounded-lg absolute block h-auto max-w-xs mx-auto -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
                      alt=""
                      width="210"
                      height="100%"
                    />
                    <figcaption class="mt-2 text-sm text-center text-gray-500 dark:text-gray-400">Front (Standard)</figcaption>
                  </div>
                  <!-- Item 2 -->
                  <div class="hidden duration-700 ease-in-out" data-carousel-item>
                    <img
                      src="/Red-frame-rear.jpg"
                      class="shadow-xl dark:shadow-gray-800 rounded-lg absolute block h-auto max-w-xs mx-auto -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
                      alt=""
                      width="210"
                      height="100%"
                    />
                    <figcaption class="mt-2 text-sm text-center text-gray-500 dark:text-gray-400">Rear (Standard)</figcaption>
                  </div>
                  <!-- Item 3 -->
                  <div class="hidden duration-700 ease-in-out" data-carousel-item>
                    <img
                      src="/Mbf-p02-flight.jpg"
                      class="shadow-xl dark:shadow-gray-800 rounded-lg absolute block h-auto max-w-xs mx-auto -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
                      alt=""
                      width="210"
                      height="100%"
                    />
                    <figcaption class="mt-2 text-sm text-center text-gray-500 dark:text-gray-400">
                      Front (w/Flight unit)
                    </figcaption>
                  </div>
                  <!-- Item 4 -->
                  <div class="hidden duration-700 ease-in-out" data-carousel-item>
                    <img
                      src="/Mbf-p02-flight-rear.jpg"
                      class="shadow-xl dark:shadow-gray-800 rounded-lg absolute block h-auto max-w-xs mx-auto -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
                      alt=""
                      width="210"
                      height="100%"
                    />
                    <figcaption class="mt-2 text-sm text-center text-gray-500 dark:text-gray-400">
                      Rear (w/Flight unit)
                    </figcaption>
                  </div>
                  <!-- Item 5 -->
                  <div class="hidden duration-700 ease-in-out" data-carousel-item>
                    <img
                      src="/Mbf-p02-salvage.jpg"
                      class="shadow-xl dark:shadow-gray-800 rounded-lg absolute block h-auto max-w-xs mx-auto -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
                      alt=""
                      width="210"
                      height="100%"
                    />
                    <figcaption class="mt-2 text-sm text-center text-gray-500 dark:text-gray-400">With Salvage unit</figcaption>
                  </div>
                </div>
                <div class="flex justify-center items-center pt-4">
                  <button
                    type="button"
                    class="flex justify-center items-center mr-4 h-full cursor-pointer group focus:outline-none"
                    data-carousel-prev
                  >
                    <span
                      class="text-gray-400 hover:text-gray-900 dark:hover:text-white group-focus:text-gray-900 dark:group-focus:text-white"
                    >
                      <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 10">
                        <path
                          stroke="currentColor"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          stroke-width="2"
                          d="M13 5H1m0 0 4 4M1 5l4-4"
                        />
                      </svg>
                      <span class="sr-only">Previous</span>
                    </span>
                  </button>
                  <button
                    type="button"
                    class="flex justify-center items-center h-full cursor-pointer group focus:outline-none"
                    data-carousel-next
                  >
                    <span
                      class="text-gray-400 hover:text-gray-900 dark:hover:text-white group-focus:text-gray-900 dark:group-focus:text-white"
                    >
                      <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 10">
                        <path
                          stroke="currentColor"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          stroke-width="2"
                          d="M1 5h12m0 0L9 1m4 4L9 9"
                        />
                      </svg>
                      <span class="sr-only">Next</span>
                    </span>
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="hidden p-4 rounded-lg bg-gray-50 dark:bg-gray-800" id="dashboard" role="tabpanel" aria-labelledby="dashboard-tab">
      <div class="grid gap-4">
        <div>
          <!-- gundam unicorn -->
          <div class="grid md:grid-cols-2 gap-8">
            <div class="bg-gray-50 dark:bg-gray-800 border border-gray-200 dark:border-gray-700 rounded-lg p-8 md:p-12">
              <h2 class="text-gray-900 text-center dark:text-white text-3xl font-extrabold mb-2">RX-0 Unicorn Gundam</h2>
              <hr class="h-px my-8 bg-gray-200 border-0 dark:bg-gray-700" />
              <p class="text-lg font-normal text-gray-500 dark:text-gray-400 mb-4">
                The RX-0 Unicorn Gundam (ユニコーン ガンダム Yunikōn Gandamu, or Unicorn, Unicorn Gundam 01, Singularity One) is
                the titular prototype mobile suit of the Mobile Suit Gundam Unicorn novel, its OVA adaptation and the television
                re-cut. It is piloted by Banagher Links after the head of the Vist Foundation and his father, Cardeas Vist,
                entrusted it to him at the dawn of the Third Neo Zeon War in U.C. 0096.
              </p>
              <a
                href="https://gundam.fandom.com/wiki/RX-0_Unicorn_Gundam"
                class="text-blue-600 dark:text-blue-500 hover:underline font-medium text-lg inline-flex items-center"
                >Read more
                <svg
                  class="w-3.5 h-3.5 ml-2"
                  aria-hidden="true"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 14 10"
                >
                  <path
                    stroke="currentColor"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M1 5h12m0 0L9 1m4 4L9 9"
                  />
                </svg>
              </a>
            </div>
            <div class="bg-gray-50 dark:bg-gray-800 border border-gray-200 dark:border-gray-700 rounded-lg p-8 md:p-12">
              <div id="custom-controls-gallery" class="relative w-full" data-carousel="slide">
                <!-- Carousel wrapper -->
                <div class="relative h-56 overflow-hidden rounded-lg md:h-96">
                  <!-- Item 1 -->
                  <div class="hidden duration-700 ease-in-out" data-carousel-item="active">
                    <img
                      src="/Rx0uc-ova.jpg"
                      class="shadow-xl dark:shadow-gray-800 rounded-lg absolute block h-auto max-w-xs mx-auto -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
                      alt=""
                      width="210"
                      height="100%"
                    />
                    <figcaption class="mt-2 text-sm text-center text-gray-500 dark:text-gray-400">
                      Front (Unicorn Mode)
                    </figcaption>
                  </div>
                  <!-- Item 2 -->
                  <div class="hidden duration-700 ease-in-out" data-carousel-item>
                    <img
                      src="/Rx0uc-ova-rear.jpg"
                      class="shadow-xl dark:shadow-gray-800 rounded-lg absolute block h-auto max-w-xs mx-auto -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
                      alt=""
                      width="210"
                      height="100%"
                    />
                    <figcaption class="mt-2 text-sm text-center text-gray-500 dark:text-gray-400">Rear (Unicorn Mode)</figcaption>
                  </div>
                  <!-- Item 3 -->
                  <div class="hidden duration-700 ease-in-out" data-carousel-item>
                    <img
                      src="/Rxuc-ova-ntd.jpg"
                      class="shadow-xl dark:shadow-gray-800 rounded-lg absolute block h-auto max-w-xs mx-auto -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
                      alt=""
                      width="210"
                      height="100%"
                    />
                    <figcaption class="mt-2 text-sm text-center text-gray-500 dark:text-gray-400">
                      Front (Destroy Mode)
                    </figcaption>
                  </div>
                  <!-- Item 4 -->
                  <div class="hidden duration-700 ease-in-out" data-carousel-item>
                    <img
                      src="/Rx0uc-ova-ntd-rear.jpg"
                      class="shadow-xl dark:shadow-gray-800 rounded-lg absolute block h-auto max-w-xs mx-auto -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
                      alt=""
                      width="210"
                      height="100%"
                    />
                    <figcaption class="mt-2 text-sm text-center text-gray-500 dark:text-gray-400">Rear (Destroy Mode)</figcaption>
                  </div>
                  <!-- Item 5 -->
                  <div class="hidden duration-700 ease-in-out" data-carousel-item>
                    <img
                      src="/Deactivated_Gundam_Unicorn.jpg"
                      class="shadow-xl dark:shadow-gray-800 rounded-lg absolute block h-auto max-w-xs mx-auto -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
                      alt=""
                      width="210"
                      height="100%"
                    />
                    <figcaption class="mt-2 text-sm text-center text-gray-500 dark:text-gray-400">
                      Front (Psycho-Frame Deactivated)
                    </figcaption>
                  </div>
                  <!-- Item 6 -->
                  <div class="hidden duration-700 ease-in-out" data-carousel-item>
                    <img
                      src="/Axis_Shock_Gundam_Unicorn.jpg"
                      class="shadow-xl dark:shadow-gray-800 rounded-lg absolute block h-auto max-w-xs mx-auto -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
                      alt=""
                      width="210"
                      height="100%"
                    />
                    <figcaption class="mt-2 text-sm text-center text-gray-500 dark:text-gray-400">
                      Front ("Awakened" Destroy Mode)
                    </figcaption>
                  </div>
                </div>
                <div class="flex justify-center items-center pt-4">
                  <button
                    type="button"
                    class="flex justify-center items-center mr-4 h-full cursor-pointer group focus:outline-none"
                    data-carousel-prev
                  >
                    <span
                      class="text-gray-400 hover:text-gray-900 dark:hover:text-white group-focus:text-gray-900 dark:group-focus:text-white"
                    >
                      <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 10">
                        <path
                          stroke="currentColor"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          stroke-width="2"
                          d="M13 5H1m0 0 4 4M1 5l4-4"
                        />
                      </svg>
                      <span class="sr-only">Previous</span>
                    </span>
                  </button>
                  <button
                    type="button"
                    class="flex justify-center items-center h-full cursor-pointer group focus:outline-none"
                    data-carousel-next
                  >
                    <span
                      class="text-gray-400 hover:text-gray-900 dark:hover:text-white group-focus:text-gray-900 dark:group-focus:text-white"
                    >
                      <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 10">
                        <path
                          stroke="currentColor"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          stroke-width="2"
                          d="M1 5h12m0 0L9 1m4 4L9 9"
                        />
                      </svg>
                      <span class="sr-only">Next</span>
                    </span>
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="hidden p-4 rounded-lg bg-gray-50 dark:bg-gray-800" id="settings" role="tabpanel" aria-labelledby="settings-tab">
      <div class="grid gap-4">
        <div>
          <!-- gundam strike freedom -->
          <div class="grid md:grid-cols-2 gap-8">
            <div class="bg-gray-50 dark:bg-gray-800 border border-gray-200 dark:border-gray-700 rounded-lg p-8 md:p-12">
              <h2 class="text-gray-900 text-center dark:text-white text-3xl font-extrabold mb-2">
                ZGMF-X20A Strike Freedom Gundam
              </h2>
              <hr class="h-px my-8 bg-gray-200 border-0 dark:bg-gray-700" />
              <p class="text-lg font-normal text-gray-500 dark:text-gray-400 mb-4">
                The ZGMF-X20A Strike Freedom Gundam (aka Strike Freedom, Freedom) is the successor of the ZGMF-X10A Freedom Gundam
                introduced in the anime Mobile Suit Gundam SEED Destiny. It is piloted by Kira Yamato.
                <br /><br />
                A mobile suit tuned to meet Kira Yamato's needs, the Strike Freedom has Variable Phase Shift armor, and like its
                predecessor, ZGMF-X10A Freedom Gundam, is primarily armed with powerful ranged weapons.
              </p>
              <a
                href="https://gundam.fandom.com/wiki/ZGMF-X20A_Strike_Freedom_Gundam"
                class="text-blue-600 dark:text-blue-500 hover:underline font-medium text-lg inline-flex items-center"
                >Read more
                <svg
                  class="w-3.5 h-3.5 ml-2"
                  aria-hidden="true"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 14 10"
                >
                  <path
                    stroke="currentColor"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M1 5h12m0 0L9 1m4 4L9 9"
                  />
                </svg>
              </a>
            </div>
            <div class="bg-gray-50 dark:bg-gray-800 border border-gray-200 dark:border-gray-700 rounded-lg p-8 md:p-12">
              <div id="custom-controls-gallery" class="relative w-full" data-carousel="slide">
                <!-- Carousel wrapper -->
                <div class="relative h-56 overflow-hidden rounded-lg md:h-96">
                  <!-- Item 1 -->
                  <div class="hidden duration-700 ease-in-out" data-carousel-item="active">
                    <img
                      src="/Strike_freedom_front_lineart_color.jpg"
                      class="shadow-xl dark:shadow-gray-800 rounded-lg absolute block h-auto max-w-xs mx-auto -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
                      alt=""
                      width="210"
                      height="100%"
                    />
                    <figcaption class="mt-2 text-sm text-center text-gray-500 dark:text-gray-400">Front</figcaption>
                  </div>
                  <!-- Item 2 -->
                  <div class="hidden duration-700 ease-in-out" data-carousel-item>
                    <img
                      src="/Strike-freedom-rear.jpg"
                      class="shadow-xl dark:shadow-gray-800 rounded-lg absolute block h-auto max-w-xs mx-auto -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
                      alt=""
                      width="210"
                      height="100%"
                    />
                    <figcaption class="mt-2 text-sm text-center text-gray-500 dark:text-gray-400">Rear</figcaption>
                  </div>
                </div>
                <div class="flex justify-center items-center pt-4">
                  <button
                    type="button"
                    class="flex justify-center items-center mr-4 h-full cursor-pointer group focus:outline-none"
                    data-carousel-prev
                  >
                    <span
                      class="text-gray-400 hover:text-gray-900 dark:hover:text-white group-focus:text-gray-900 dark:group-focus:text-white"
                    >
                      <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 10">
                        <path
                          stroke="currentColor"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          stroke-width="2"
                          d="M13 5H1m0 0 4 4M1 5l4-4"
                        />
                      </svg>
                      <span class="sr-only">Previous</span>
                    </span>
                  </button>
                  <button
                    type="button"
                    class="flex justify-center items-center h-full cursor-pointer group focus:outline-none"
                    data-carousel-next
                  >
                    <span
                      class="text-gray-400 hover:text-gray-900 dark:hover:text-white group-focus:text-gray-900 dark:group-focus:text-white"
                    >
                      <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 10">
                        <path
                          stroke="currentColor"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          stroke-width="2"
                          d="M1 5h12m0 0L9 1m4 4L9 9"
                        />
                      </svg>
                      <span class="sr-only">Next</span>
                    </span>
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style></style>

<script>
import { Tabs } from "flowbite";

const tabElements = [
  {
    id: "profile",
    triggerEl: document.querySelector("#profile-tab-example"),
    targetEl: document.querySelector("#profile-example"),
  },
  {
    id: "dashboard",
    triggerEl: document.querySelector("#dashboard-tab-example"),
    targetEl: document.querySelector("#dashboard-example"),
  },
  {
    id: "settings",
    triggerEl: document.querySelector("#settings-tab-example"),
    targetEl: document.querySelector("#settings-example"),
  },
  {
    id: "contacts",
    triggerEl: document.querySelector("#contacts-tab-example"),
    targetEl: document.querySelector("#contacts-example"),
  },
];

// options with default values
const options = {
  defaultTabId: "settings",
  activeClasses:
    "text-blue-600 hover:text-blue-600 dark:text-blue-500 dark:hover:text-blue-400 border-blue-600 dark:border-blue-500",
  inactiveClasses:
    "text-gray-500 hover:text-gray-600 dark:text-gray-400 border-gray-100 hover:border-gray-300 dark:border-gray-700 dark:hover:text-gray-300",
  onShow: () => {
    console.log("tab is shown");
  },
};
</script>
