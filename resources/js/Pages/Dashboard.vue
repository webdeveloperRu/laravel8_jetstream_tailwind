<template>
  <app-layout>
    <!-- @section A part -->
    <div class="flex flex-wrap items-center">
      <div class="w-full md:w-1/2 xl:w-1/4 p-3">
        <!--Metric Card-->
        <div class="bg-gray-900 border border-gray-800 rounded shadow p-2">
          <div class="flex flex-row items-center">
            <div class="flex-shrink pr-4">
              <div class="rounded p-3 bg-green-600">
                <i class="fa fa-wallet fa-2x fa-fw fa-inverse"></i>
              </div>
            </div>
            <div class="flex-1 text-right md:text-center">
              <h5 class="font-bold uppercase text-gray-400">Total Revenue</h5>
              <h3 class="font-bold text-3xl text-gray-600">
                $3249
                <span class="text-green-500"
                  ><i class="fas fa-caret-up"></i
                ></span>
              </h3>
            </div>
          </div>
        </div>
        <!--/Metric Card-->
      </div>

      <div class="w-full md:w-1/2 xl:w-1/4 p-3">
        <!--Metric Card-->
        <div class="bg-gray-900 border border-gray-800 rounded shadow p-2">
          <div class="flex flex-row items-center">
            <div class="flex-shrink pr-4">
              <div class="rounded p-3 bg-green-600">
                <i class="fa fa-wallet fa-2x fa-fw fa-inverse"></i>
              </div>
            </div>
            <div class="flex-1 text-right md:text-center">
              <h5 class="font-bold uppercase text-gray-400">Total Revenue</h5>
              <h3 class="font-bold text-3xl text-gray-600">
                $3249
                <span class="text-green-500"
                  ><i class="fas fa-caret-up"></i
                ></span>
              </h3>
            </div>
          </div>
        </div>
        <!--/Metric Card-->
      </div>

      <div class="w-full md:w-1/2 xl:w-1/4 p-3">
        <!--Metric Card-->
        <div class="bg-gray-900 border border-gray-800 rounded shadow p-2">
          <div class="flex flex-row items-center">
            <div class="flex-shrink pr-4">
              <div class="rounded p-3 bg-green-600">
                <i class="fa fa-wallet fa-2x fa-fw fa-inverse"></i>
              </div>
            </div>
            <div class="flex-1 text-right md:text-center">
              <h5 class="font-bold uppercase text-gray-400">Total Revenue</h5>
              <h3 class="font-bold text-3xl text-gray-600">
                $3249
                <span class="text-green-500"
                  ><i class="fas fa-caret-up"></i
                ></span>
              </h3>
            </div>
          </div>
        </div>
        <!--/Metric Card-->
      </div>

      <div class="w-full md:w-1/2 xl:w-1/4 p-3">
        <!--Metric Card-->
        <div class="bg-gray-900 border border-gray-800 rounded shadow p-2">
          <div class="flex flex-row items-center">
            <div class="flex-shrink pr-4">
              <div class="rounded p-3 bg-green-600">
                <i class="fa fa-wallet fa-2x fa-fw fa-inverse"></i>
              </div>
            </div>
            <div class="flex-1 text-right md:text-center">
              <h5 class="font-bold uppercase text-gray-400">Total Revenue</h5>
              <h3 class="font-bold text-3xl text-gray-600">
                $3249
                <span class="text-green-500"
                  ><i class="fas fa-caret-up"></i
                ></span>
              </h3>
            </div>
          </div>
        </div>
        <!--/Metric Card-->
      </div>
    </div>
    <!-- section A part end -->

    <!-- Graph Part Start -->
    <div class="flex flex-row flex-wrap flex-grow mt-2">
      <div class="w-full md:w-1/3 p-3">
        <!--Graph Card-->
        <div class="bg-gray-900 border border-gray-800 rounded shadow">
          <div class="border-b border-gray-800 p-3">
            <h5 class="font-bold uppercase text-gray-600">Graph</h5>
          </div>
          <div class="p-5"></div>
        </div>
        <!--/Graph Card-->
      </div>

      <div class="w-full md:w-2/3 p-3">
        <!--Graph Card-->
        <div class="bg-gray-900 border border-gray-800 rounded shadow">
          <div class="border-b border-gray-800 p-3">
            <h5 class="font-bold uppercase text-gray-600">Graph</h5>
          </div>
          <div class="p-5"></div>
        </div>
        <!--/Graph Card-->
      </div>
    </div>
    <!-- Graph part -->

    <!-- Section B Part Start -->
    <div class="flex flex-row flex-wrap flex-grow mt-2">
      <div class="w-full p-3">
        <div class="bg-gray-900 border border-gray-800 rounded shadow">
          <div class="border-b border-gray-800 p-3">
            <h5 class="font-bold uppercase text-gray-600">Graph</h5>
          </div>
          <div class="p-5"></div>
        </div>
      </div>
    </div>
    <!-- Section B Part End -->
  </app-layout>
</template>

<script>
import AppLayout from "@/Layouts/AppLayout";

export default {
  components: {
    AppLayout,
  },
};
</script>
