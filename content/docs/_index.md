---
title: Guides
weight: 1
toc: false
breadcrumbs: false
type: netduma-wide
---

<div class="flex gap-8 mt-4">
  <div class="flex-1 basis-1/5">
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
  <div class="flex-1 flex flex-col gap-2">
    <h2 class="m-0">Section title here</h2>
    <div>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</div>
    {{< netduma/button class="mt-2" buttonColor="primary" text="Button here" link="#" >}}
  </div>
</div>

{{< callout icon="r3" >}}
  Netduma R3 users should select DumaOS 4.
{{< /callout >}}

{{< netduma/cards class="my-6" cols="4">}}
  {{< netduma/card
    span="2" 
    title="DumaOS 4" 
    subtitle="Frequently Asked Questions about Netduma, DumaOS and networking in general" 
    image="/images/dumaos4-devicemanager.jpg"
    link="../docs/dumaos-4/"
  >}}
  {{< /netduma/card >}}
  {{< netduma/card
    span="2" 
    title="DumaOS 3" 
    subtitle="Frequently Asked Questions about Netduma, DumaOS and networking in general" 
    image="/images/dumaos3-devicemanager.jpg"
    link="../docs/dumaos-3/"
  >}}
  {{< /netduma/card >}}
  {{< netduma/card
    span="2" 
    title="Telstra Game Optimiser" 
    subtitle="Frequently Asked Questions about Netduma, DumaOS and networking in general" 
    class="bg-[white]"
    image="/images/dumaos-telstra.jpg"
    link="../docs/telstra-game-optimiser/"
  >}}
  {{< /netduma/card >}}
  {{< netduma/cards class="lg:col-span-2">}}
    {{< netduma/card
      span="4"
      title="User Manuals" 
      subtitle="User manuals for DumaOS compatible hardware" 
      class="bg-[white]"
      link="../docs/user-manuals/"
    >}}
    {{< /netduma/card >}}
    {{< netduma/card
      span="4"
      title="Supported Applications" 
      class="bg-[white]"
      link="../docs/supported-applications/"
    >}}
    {{< /netduma/card >}}
  {{< /netduma/cards >}}

{{< /netduma/cards >}}