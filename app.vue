<template>
    <ProfileInfo
        :photo="photo"
        title="Antonio Carvalho"
        subtitle="@antoniogsc"
        headline="Front-end Developer"
    />
   
    <div class="max-w-xs mx-auto">
        <ButtonAction 
            text="Website"
            link="https://www.antoniocarvalho.dev"
            icon="💬"
        />
        <ButtonAction 
            text="Linkedin"
            link="https://www.linkedin.com/in/antoniogscarvalho/"
            icon="💼"
        />
        <ButtonAction 
            text="Github"
            link="https://github.com/AntonioGSC"
            icon="🛠"
        />
    </div>
</template>

<script setup>
    import photo from "./assets/profile.png";
</script>
