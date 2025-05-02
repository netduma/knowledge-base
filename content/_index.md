---
layout: index
---

<!-- markdownlint-disable-next-line MD041 -->
<div class="my-16 container mx-auto max-w-screen-sm text-center flex flex-col gap-4">
  <h1 class="text-5xl tracking-wide">Netduma Knowledge Base</h1>
  <div class="text-text-secondary tracking-wide">Welcome to the Netduma support site. Here you'll find guides for all of our features, along with frequently asked questions and useful links.</div>
</div>


<div class="text-center flex flex-col items-center gap-4 my-16">
  <label for="search" class="text-2xl font-semibold tracking-wide">Search for Topics</label>
 <input class="max-w-xl w-full rounded-md grow py-2 px-3 shadow-sm focus:outline-none" placeholder="Search Knowledge Base" type="text" name="search"/>
</div>

{{< netduma/cards cols="6" class="mt-6">}}
  {{< netduma/card
    span="2" 
    title="Netduma R3" 
    subtitle="Frequently Asked Questions about Netduma, DumaOS and networking in general" 
    image="/images/R3-Render.png"
    imageClass="pt-4 px-4"
  >}}
    {{< netduma/card-links >}}
      {{< netduma/card-link title="Firmwares" link="platforms/r3/firmware" >}}
      {{< netduma/card-link title="DumaOS 4 Guides" link="docs/dumaos-4" >}}
      {{< netduma/card-link title="DumaOS 4 FAQs" link="frequently-asked-questions/dumaos4" >}}
    {{< /netduma/card-links >}}
    {{< netduma/button link="platforms/r3" buttonColor="primary" text="View More" >}}
  {{< /netduma/card >}}
  {{< netduma/card
    span="2" 
    title="Netduma R2" 
    subtitle="Frequently Asked Questions about Netduma, DumaOS and networking in general"
    image="/images/R2-Render.png"
    imageClass="pt-4 px-4"
  >}}
    {{< netduma/card-links >}}
      {{< netduma/card-link title="Firmwares" link="platforms/r2/firmware" >}}
      {{< netduma/card-link title="DumaOS 3 Guides" link="docs/dumaos-3" >}}
      {{< netduma/card-link title="DumaOS 3 FAQs" link="frequently-asked-questions/dumaos3" >}}
    {{< /netduma/card-links >}}
    {{< netduma/button link="platforms/r2" buttonColor="primary" text="View More" >}}
  {{< /netduma/card >}}
  {{< netduma/card
    span="2" 
    title="Other Platforms" 
    subtitle="Get support for platforms not listed elsewhere" 
    link=""
  >}}
    {{< netduma/card-links >}}
      {{< netduma/card-link title="Netduma R1" link="platforms/r1" >}}
      {{< netduma/card-link title="Netgear Nighthawk" link="platforms/netgear-nighthawk" >}}
      {{< netduma/card-link title="Telstra" link="platforms/telstra" >}}
    {{< /netduma/card-links >}}
  {{< /netduma/card >}}
{{< /netduma/cards >}}

{{< netduma/grid title="DumaOS" align="center" class="mt-16" >}}  
  {{< netduma/grid-icon link="docs/dumaos-4" title="DumaOS 4" icon="dumaos4" >}}
  {{< netduma/grid-icon link="docs/dumaos-3" title="DumaOS 3" icon="dumaos3" >}}
  {{< netduma/grid-icon link="docs/telstra-internet-optimiser" title="Telstra" icon="telstra" >}}
{{< /netduma/grid >}}

{{< netduma/grid title="Still need Help?" subtitle="We are always available via email and via our support forums. Our friendly support team will answer any questions you have about Netduma, DumaOS or networking in general." align="center" class="mt-32" >}}  
  {{< netduma/grid-icon link="mailto:netduma@netduma.com" title="Email" icon="email" >}}
  {{< netduma/grid-icon link="https://forum.netduma.com/" title="Forum" icon="forum" >}}
  {{< netduma/grid-icon link="https://www.youtube.com/netduma" title="Youtube" icon="youtube" >}}
{{< /netduma/grid >}}
