---
layout: index
---

<!-- markdownlint-disable-next-line MD041 -->
<div class="py-16 container mx-auto max-w-screen-sm text-center flex flex-col gap-4">
  <h1 class="text-5xl tracking-wide">Netduma Knowledge Base</h1>
  <div class="text-text-secondary tracking-wide">Welcome to the Netduma support site. Here you'll find guides for all of our features, along with frequently asked questions and useful links.</div>
</div>

{{< netduma/cards cols="6" class="py-16" title="Get Started">}}
  {{< netduma/button-card 
    span="2" 
    link="../#" 
    title="DumaOS 4" 
    subtitle="Frequently Asked Questions about Netduma, DumaOS and networking in general" 
    buttonText="Something Here" 
    image="/images/R3-Render.png" 
    imagePos="top" 
    imageClass="mx-0 mb-6" 
  >}}
  {{< netduma/button-card 
    span="2" 
    link="../#" 
    title="DumaOS 3.0" 
    subtitle="Frequently Asked Questions about Netduma, DumaOS and networking in general" 
    buttonText="Something Here" 
    image="/images/R2-Render.png" 
    imagePos="top" 
    imageClass="mx-0 mb-6" >}}
  {{< netduma/button-card 
    span="2" 
    link="../#" 
    title="Telstra Game Optimiser" 
    subtitle="Frequently Asked Questions about Netduma, DumaOS and networking in general" 
    buttonColor="secondary" 
    buttonText="Something Here"
    class="bg-[white]"
    image="/images/telstra-render.png" 
    imagePos="top" 
    imageClass="mx-0 mb-6" 
  >}}
{{< /netduma/cards >}}

<div class="text-center flex flex-col items-center gap-4 py-16">
  <label for="search" class="text-2xl font-semibold tracking-wide">Search for Topics</label>
 <input class="max-w-xl w-full rounded-md grow py-2 px-3 shadow-sm focus:outline-none" placeholder="Search Knowledge Base" type="text" name="search"/>
</div>

<div class="flex flex-col-reverse md:flex-row gap-12 py-16">
  <div class="basis-2/3">
    {{< netduma/cards cols="6">}}  
      {{< netduma/card span="3" link="../frequently-asked-questions" title="FAQs" icon="faq" subtitle="Frequently Asked Questions about Netduma, DumaOS and networking in general" >}}
      {{< netduma/card span="3" link="../docs/user-manuals" title="User Manuals" icon="grid" subtitle="User manuals for DumaOS compatible hardware" >}}
      {{< netduma/card span="3" link="../firmwares" title="Firmwares" icon="firmware" subtitle="Get the latest updates for DumaOS" >}}
    {{< /netduma/cards >}}
  </div>
  <div class="basis-1/3">
      {{< netduma/tabs items="POPULAR,RECENT" >}}
        {{< netduma/tab >}}  
          <div class="flex flex-col gap-2">
            <a class="text-xl font-semibold tracking-wide text-text-primary hover:text-primary-main transition-colors no-underline cursor-pointer">Call of Duty Optimisation Guide</a>
            <div class="flex gap-4 text-sm text-white/65">
              <a class="text-text-secondary hover:text-text-primary transition-colors no-underline cursor-pointer">DumaOS</a>
              <a class="text-text-secondary hover:text-text-primary transition-colors no-underline cursor-pointer">Game Guide</a>
            </div>
          </div>
          <div class="flex flex-col gap-2">
            <a class="text-xl font-semibold tracking-wide text-text-primary hover:text-primary-main transition-colors no-underline cursor-pointer">Call of Duty Optimisation Guide</a>
            <div class="flex gap-4 text-sm text-white/65">
              <a class="text-text-secondary hover:text-text-primary transition-colors no-underline cursor-pointer">DumaOS</a>
              <a class="text-text-secondary hover:text-text-primary transition-colors no-underline cursor-pointer">Game Guide</a>
            </div>
          </div>
          <div class="flex flex-col gap-2">
            <a class="text-xl font-semibold tracking-wide text-text-primary hover:text-primary-main transition-colors no-underline cursor-pointer">Ping Heatmap</a>
            <div class="flex gap-4 text-sm text-white/65">
              <a class="text-text-secondary hover:text-text-primary transition-colors no-underline cursor-pointer">DumaOS</a>
              <a class="text-text-secondary hover:text-text-primary transition-colors no-underline cursor-pointer">Features</a>
            </div>
          </div>
          <div class="flex flex-col gap-2">
            <a class="text-xl font-semibold tracking-wide text-text-primary hover:text-primary-main transition-colors no-underline cursor-pointer">Halo Optimisation Guide</a>
            <div class="flex gap-4 text-sm text-white/65">
              <a class="text-text-secondary hover:text-text-primary transition-colors no-underline cursor-pointer">DumaOS</a>
              <a class="text-text-secondary hover:text-text-primary transition-colors no-underline cursor-pointer">Game Guide</a>
            </div>
          </div>
        {{< /netduma/tab >}}
        {{< netduma/tab >}}
          <div class="flex flex-col gap-2">
            <a class="text-xl font-semibold tracking-wide text-text-primary hover:text-primary-main transition-colors no-underline cursor-pointer">Geo-Filter</a>
            <div class="flex gap-4 text-sm text-white/65">
              <a class="text-text-secondary hover:text-text-primary transition-colors no-underline cursor-pointer">DumaOS 4</a>
              <a class="text-text-secondary hover:text-text-primary transition-colors no-underline cursor-pointer">Features</a>
            </div>
          </div>
          <div class="flex flex-col gap-2">
            <a class="text-xl font-semibold tracking-wide text-text-primary hover:text-primary-main transition-colors no-underline cursor-pointer">Call of Duty Optimisation Guide</a>
            <div class="flex gap-4 text-sm text-white/65">
              <a class="text-text-secondary hover:text-text-primary transition-colors no-underline cursor-pointer">DumaOS 4</a>
              <a class="text-text-secondary hover:text-text-primary transition-colors no-underline cursor-pointer">Game Guide</a>
            </div>
          </div>
        {{< /netduma/tab >}}
      {{</ netduma/tabs >}}
  </div>
</div>

<div class="py-16 container mx-auto max-w-screen-sm text-center">
  <div class="text-2xl font-semibold tracking-wide">Still need Help?</div>
  <p class="text-text-secondary">We are always available via email and via our support forums. Our friendly support team will answer any questions you have about Netduma, DumaOS or networking in general.</p>
    {{< netduma/grid class="justify-center py-8" >}}  
      {{< netduma/grid-icon link="../#" title="Email" icon="email" >}}
      {{< netduma/grid-icon link="../#" title="Forum" icon="forum" >}}
      {{< netduma/grid-icon link="../#" title="Youtube" icon="youtube" >}}
    {{< /netduma/grid >}}  
</div>
