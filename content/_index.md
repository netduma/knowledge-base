---
layout: index
---

<!-- markdownlint-disable-next-line MD041 -->
<div class="py-16 container mx-auto max-w-screen-sm text-center flex flex-col gap-4">
  <h1 class="text-5xl tracking-wide">Netduma Knowledge Base</h1>
  <div class="text-text-secondary tracking-wide">Welcome to the Netduma support site. Here you'll find guides for all of our features, along with frequently asked questions and useful links.</div>
</div>

{{< netduma/cards cols="6" title="Hardware">}}
  {{< netduma/card
    span="2" 
    title="Netduma R3" 
    subtitle="Frequently Asked Questions about Netduma, DumaOS and networking in general" 
    image="/images/R3-Render.png"
    imageClass="pt-4 px-4"
    link="../hardware/r3"
  >}}
  {{< /netduma/card >}}
  {{< netduma/card
    span="2" 
    title="Netduma R2" 
    subtitle="Frequently Asked Questions about Netduma, DumaOS and networking in general"
    image="/images/R2-Render.png"
    imageClass="pt-4 px-4"
    link="../hardware/r2"
  >}}
  {{< /netduma/card >}}
  {{< netduma/card
    span="2" 
    title="Telstra Modem" 
    subtitle="Frequently Asked Questions about Netduma, DumaOS and networking in general"
    image="/images/telstra-render.png"
    imageClass="pt-4 px-4"
    link="../hardware/telstra"
  >}}
  {{< /netduma/card >}}
{{< /netduma/cards >}}

{{< netduma/grid title="DumaOS" class="mt-16" >}}  
  {{< netduma/grid-icon link="../docs/dumaos-4" title="DumaOS 4" icon="dumaos4" >}}
  {{< netduma/grid-icon link="../docs/dumaos-3" title="DumaOS 3" icon="dumaos3" >}}
  {{< netduma/grid-icon link="../docs/telstra-game-optimiser" title="Telstra" icon="telstra" >}}
{{< /netduma/grid >}}

<div class="text-center flex flex-col items-center gap-4 py-16">
  <label for="search" class="text-2xl font-semibold tracking-wide">Search for Topics</label>
 <input class="max-w-xl w-full rounded-md grow py-2 px-3 shadow-sm focus:outline-none" placeholder="Search Knowledge Base" type="text" name="search"/>
</div>

<div class="flex flex-col-reverse md:flex-row gap-12 py-16">
  <div class="basis-3/5">
    {{< netduma/cards cols="6">}}
      {{< netduma/card span="3" link="#" title="Hardware Support" subtitle="Get the latest updates for DumaOS" >}}{{< /netduma/card >}}
      {{< netduma/card span="3" link="#" title="User Manuals" subtitle="User manuals for DumaOS compatible hardware" >}}{{< /netduma/card >}}
      {{< netduma/card span="3" link="../frequently-asked-questions" title="FAQs" icon="faq" subtitle="Frequently Asked Questions about Netduma, DumaOS and networking in general" >}}{{< /netduma/card >}}
      {{< netduma/card span="3" link="../firmwares" title="Firmwares" icon="firmware" subtitle="Get the latest updates for DumaOS" >}}{{< /netduma/card >}}
    {{< /netduma/cards >}}
  </div>
  <div class="basis-2/5">
    {{< netduma/tabs items="Popular Guides,Recent Guides" >}}
      {{< netduma/tab >}}  
        <a class="my-2 text-text-primary hover:text-primary-main transition-colors no-underline cursor-pointer">Call of Duty Optimisation Guide</a>
        <a class="my-2 text-text-primary hover:text-primary-main transition-colors no-underline cursor-pointer">Call of Duty Optimisation Guide</a>
        <a class="my-2 text-text-primary hover:text-primary-main transition-colors no-underline cursor-pointer">Ping Heatmap</a>
        <a class="my-2 text-text-primary hover:text-primary-main transition-colors no-underline cursor-pointer">Halo Optimisation Guide</a>
      {{< /netduma/tab >}}
      {{< netduma/tab >}}
        <a class="my-2 text-text-primary hover:text-primary-main transition-colors no-underline cursor-pointer">Ping Heatmap</a>
        <a class="my-2 text-text-primary hover:text-primary-main transition-colors no-underline cursor-pointer">Halo Optimisation Guide</a>
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
