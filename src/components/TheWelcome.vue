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
    <template #heading>Education Background</template>

    I am currently studying at Riau Islamic University,
    <a href="https://uir.ac.id/" target="_blank" rel="noopener">Riau Islamic University</a>
    <br>
    and I also did a student exchange at Udayana University
    <a href="https://www.unud.ac.id/" target="_blank" rel="noopener">Udayana University</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Skill</template>
    I have quite a lot of skills, Master Ms Office, <br> Create web project,
    front end developer, and skill in graphic design.
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Community</template>

    My study program informatic Engineering <br> Here's my class instagram.<br>
    Hit me up there! <br>
    1.
    <a href="https://www.instagram.com/b1universe_?igsh=MTQ2ZmNscTI0ZmVsdA=="
      >@b1universe</a
    ><br />
    2. <a href="https://www.instagram.com/pmm3_unud_sandyaabhirama?igsh=ZGNjOWZkYTE3MQ%3D%3D&utm_source=qr"
      >@pmm3_unud_sandyaabhirama</a> <br/>
    </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Social Media</template>

    So, here are the social media that I have, <br /> If uou have question and want to visit my profie <br>
    you can check me out there! xoxo<br>
    Instagram = <a href="https://www.instagram.com/septiaheskaa?igsh=MTJzNGZhamQ5Zjh3OA%3D%3D&utm_source=qr" target="_blank" rel="noopener"
      > @septiaheskaa</a
    > <br/>
    Tiktok = <a href="https://www.tiktok.com/@heskuyy?_t=8lHHVzP0A6y&_r=1" target="_blank" rel="noopener"
      > @Heskuyy</a
    >.
  </WelcomeItem>
</template>