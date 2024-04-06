<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>DATA DIRI</template>

    Nama      :MUHAMMAD FEBRIADI<br>
    Tmpt lahir:TJ.KUDU INDAH<br>
    Tgl lahir :20-02-2004<br>

  </WelcomeItem>
<br>
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>RIWAYAT PENDIDIKAN</template>

    SD :SDN 012 KUALU<br>
    SMP:SMPN 03 TAMBANG<br>
    SMK:SMKN 01 TAMBANG
    <br />

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>HOBY</template>

   Makan <br>
   game<br>
   workout<br>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>KONTAK</template>

  telp/WA : 0852671694<br>
  email   : febriaditj06@gmail.com
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>MOTIVASI HIDUP</template>
"Makan ga makan yang penting minum"
  </WelcomeItem>
</template>
