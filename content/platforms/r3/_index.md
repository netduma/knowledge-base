---
title: Netduma R3
weight: 1
toc: false
breadcrumbs: false
cascade:
  type: docs
---

<div class="flex gap-8 mt-4 mb-16">
  <div class="flex-1 basis-1/5">
    <img src="/images/R3-Render.png" class="m-0 " alt="DumaOS 4">
  </div>
  <div class="flex-1 flex flex-col gap-2">
    <div>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</div>
    {{< netduma/button class="mt-2" buttonColor="primary" text="Button here" link="#" >}}
  </div>
</div>

{{< netduma/cards cols="6">}}
  {{< netduma/card
    span="2" 
    title="DumaOS 4 FAQs" 
    subtitle="Frequently Asked Questions about DumaOS 4 on the Netduma R3" 
    image="/images/dumaos4-devicemanager.jpg"
  >}}
    {{< netduma/button icon="network-activity" buttonColor="primary" text="DumaOS 4 Guides" link="/docs/dumaos-4/" >}}
  {{< /netduma/card >}}
  {{< netduma/card
    span="2"
    title="User Manual" 
    subtitle="User manuals for DumaOS compatible hardware" 
    class="bg-[white]"
  >}}
    {{< netduma/button buttonColor="primary" text="View" link="user-manual" >}}
  {{< /netduma/card >}}
  {{< netduma/card
    span="2"
    title="Firmware" 
    subtitle="A short paragraph about the latest firmware update to go here. Perhaps with some additional comments." 
    class="bg-[white]"
  >}}
    {{< netduma/card-links >}}
      {{< netduma/card-link title="Release Notes" link="/firmwares/netduma-r3/" >}}
    {{< /netduma/card-links >}}
    {{< netduma/button link="https://forum.netduma.com/topic/57039-new-r3-firmware-dumaos-40290/" buttonColor="primary" text="v.4.0.290" >}}
  {{< /netduma/card >}}
{{< /netduma/cards >}}