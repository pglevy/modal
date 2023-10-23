---
title: Choice List
---

<div id="box" class="mx-auto border border-gray-300 py-10 px-12 rounded-md">

<section class="grid grid-cols-4 mt-0 mb-4">
<h1 class="col-start-2 col-span-3 mb-1 text-3xl font-bold">Add Choice list</h1>
<p class="col-start-2 col-span-3 mt-0">Use the default values or create your own. We’ll create a new record to store the list and add a relationship from this record type to the new one.</p>
</section>

<section class="mt-0 mb-4 grid grid-cols-4 items-center">
<label class="col-span-1 font-semibold mb-1 text-gray-700 mr-2 text-right" for="name">Record Type Name</label>
<input class="col-span-3 mb-1 border-gray-300 rounded-sm py-3" type="text" id="name" value="Status">
<small class="col-span-3 col-start-2 block mt-0 text-gray-500">The name visible to developers</small>
</section>

<section class="mt-0 mb-4 grid grid-cols-4">
<label class="col-span-1 font-semibold mb-1 text-gray-700 mr-2 text-right" for="items">List Items</label>
<textarea class="col-span-3 w-full h-32 mb-1 border-gray-300 rounded-sm" id="items">
Low
Medium
High
</textarea>
<small class="col-span-3 col-start-2 block mt-0 text-gray-500">Values for end users to select from a list. Enter one item per line.</small>
</section>

<section class="mt-0 mb-4 grid grid-cols-4">
<div class="col-span-3 col-start-2 border border-gray-100 bg-gray-100 hover:bg-gray-200 hover:border-gray-200 w-full text-left rounded-sm font-semibold">
    <button class="text-left w-full flex px-3 py-3 ">
        <span class="inline-block flex-grow">Preview database script</span>
    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 inline-block flex-shrink inline-block">
  <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 8.25l-7.5 7.5-7.5-7.5" />
</svg>
</button>
</div>
</section>

<section class="grid grid-cols-4 gap-2 items-center">
<button class="col-start-2 border border-blue-700 bg-blue-700 px-6 py-3 rounded-md text-white">Generate</button>
<button class="border border-blue-700 px-6 py-3 rounded-md text-blue-700 ">Cancel</button>
</section>