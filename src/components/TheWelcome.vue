<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'

const openReadmeInEditor = () => fetch('/__open-in-editor?file=README.md')
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Our Services </template>

    JRF’s
    <a href="https://vuejs.org/" target="_blank" rel="noopener">Services</a>
    provides you with all information you need to get started.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Why Choose Us</template>

    Connecting Top Talent with the Best Opportunities – A Professional, Trustworthy, and Experienced Job Recruitment Platform!

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Strong Ecosystem</template>
    JRF Intelligent Co. Ltd – Your Trusted Recruitment Partner!

We specialize in seamless hiring and career growth with a strong ecosystem that connects top talent to the right opportunities. 
    
    <br>
Whether you are:
<br>
✅ An employer seeking highly skilled professionals
<br>
✅ A job seeker looking for your next career move
<br>
✅ An organization needing workforce solutions
<br>
Whether you're an employer, job seeker, or organization, we ensure efficient, professional, and trustworthy recruitment.
 </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact Us</template>

    At JRF Recruitment, a strong wing of JRF Intelligent Co. Ltd, we specialize in connecting top talent , we’re here to help!

<br>📞 Contact us today for a ✅ FREE consultation! <br> Let’s discuss how we can support your recruitment needs and career goals.
<!-- 
    Got stuck? Ask your question on
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener">Vue Land</a>
    (our official Discord server), or
    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener"
      >StackOverflow</a
    >. You should also follow the official
    <a href="https://bsky.app/profile/vuejs.org" target="_blank" rel="noopener">@vuejs.org</a>
    Bluesky account or the
    <a href="https://x.com/vuejs" target="_blank" rel="noopener">@vuejs</a>
    X account for latest news in the Vue world. -->
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>About us</template>

    JRF Recruitment is a strong wing of JRF Intelligent Co. Ltd, specializing in professional, trustworthy, and experienced job recruitment. With a robust ecosystem, we seamlessly connect top talent with the right opportunities, empowering businesses and job seekers alike.
  </WelcomeItem>
</template>
