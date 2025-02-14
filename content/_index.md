---
layout: index
---

<!-- markdownlint-disable-next-line MD041 -->
<div class="py-16 container mx-auto max-w-screen-sm text-center flex flex-col gap-4">
  <h1 class="text-5xl tracking-wide">Netduma Knowledge Base</h1>
  <div class="text-text-secondary tracking-wide">Welcome to the Netduma support site. Here you'll find guides for all of our features, along with frequently asked questions and useful links.</div>
</div>

<div class="flex flex-col lg:flex-row gap-16 justify-center py-16">
  {{< netduma/grid-icons title="DumaOS" >}}  
    {{< netduma/grid-icon link="../#" title="DumaOS 4" icon="r3" >}}
    {{< netduma/grid-icon link="../#" title="DumaOS 3.0" icon="test" >}}
    {{< netduma/grid-icon link="../#" title="Telstra" icon="test" >}}
  {{< /netduma/grid-icons >}}
  <div class="border-r border-white/20"></div>
  {{< netduma/grid-icons title="Hardware">}}  
    {{< netduma/grid-icon link="../#" title="Netduma R3" icon="r3" >}}
    {{< netduma/grid-icon link="../#" title="Netduma R2" icon="test" >}}
  {{< /netduma/grid-icons >}}
</div>

<div class="text-center flex flex-col items-center gap-4 py-16">
  <label for="search" class="text-2xl font-semibold tracking-wide">Search for Topics</label>
 <input class="max-w-xl w-full rounded-md grow py-2 px-3 shadow-sm focus:outline-none" placeholder="Search Knowledge Base" type="text" name="search"/>
</div>

<div class="flex flex-col-reverse md:flex-row gap-8 py-16">
  <div class="basis-2/3">
    {{< netduma/cards cols="6">}}  
      {{< netduma/card span="2" link="../#" title="FAQs" icon="r3" subtitle="Frequently Asked Questions about Netduma, DumaOS and networking in general" >}}
      {{< netduma/card span="2" link="../#" title="Firmwares" icon="test" subtitle="Get the latest updates for DumaOS" >}}
      {{< netduma/card span="2" link="../#" title="User Manuals" icon="test" subtitle="User manuals for DumaOS compatible hardware" >}}
      {{< netduma/card span="3" link="../#" title="FAQs" icon="test" subtitle="Frequently Asked Questions about Netduma, DumaOS and networking in general" >}}
      {{< netduma/card span="3" link="../#" title="FAQs" icon="test" subtitle="Frequently Asked Questions about Netduma, DumaOS and networking in general" >}}
    {{< /netduma/cards >}}
  </div>

  <div class="basis-1/3">
      {{< netduma/tabs items="POPULAR,RECENT" >}}
        {{< netduma/tab >}}  
          <div class="flex flex-col gap-2">
            <div class="text-xl font-semibold tracking-wide">Call of Duty Optimisation Guide</div>
            <div class="flex gap-4 text-sm text-white/65">
              <div>DumaOS</div>
              <div>Game Guide</div>
            </div>
          </div>
          <div class="flex flex-col gap-2">
            <div class="text-xl font-semibold tracking-wide">Call of Duty Optimisation Guide</div>
            <div class="flex gap-4 text-sm text-white/65">
              <div>DumaOS</div>
              <div>Game Guide</div>
            </div>
          </div>
          <div class="flex flex-col gap-2">
            <div class="text-xl font-semibold tracking-wide">Ping Heatmap</div>
            <div class="flex gap-4 text-sm text-white/65">
              <div>DumaOS</div>
              <div>Features</div>
            </div>
          </div>
          <div class="flex flex-col gap-2">
            <div class="text-xl font-semibold tracking-wide">Halo Optimisation Guide</div>
            <div class="flex gap-4 text-sm text-white/65">
              <div>DumaOS</div>
              <div>Game Guide</div>
            </div>
          </div>
        {{< /netduma/tab >}}
        {{< netduma/tab >}}
          <div class="flex flex-col gap-2">
            <div class="text-xl font-semibold tracking-wide">Geo-Filter</div>
            <div class="flex gap-4 text-sm text-white/65">
              <div>DumaOS 4</div>
              <div>Features</div>
            </div>
          </div>
          <div class="flex flex-col gap-2">
            <div class="text-xl font-semibold tracking-wide">Call of Duty Optimisation Guide</div>
            <div class="flex gap-4 text-sm text-white/65">
              <div>DumaOS 4</div>
              <div>Game Guide</div>
            </div>
          </div>
        {{< /netduma/tab >}}
      {{</ netduma/tabs >}}
  </div>
</div>

<div class="py-16 container mx-auto max-w-screen-sm text-center">
  <div class="text-2xl font-semibold tracking-wide">Still need Help?</div>
  <p class="text-text-secondary">We are always available via email and via our support forums. Our friendly support team will answer any questions you have about Netduma, DumaOS or networking in general.</p>
    {{< netduma/grid-icons class="justify-center py-8" >}}  
      {{< netduma/grid-icon link="../#" title="Email" icon="email" >}}
      {{< netduma/grid-icon link="../#" title="Forum" icon="forum" >}}
      {{< netduma/grid-icon link="../#" title="Youtube" icon="youtube" >}}
    {{< /netduma/grid-icons >}}  
</div>
