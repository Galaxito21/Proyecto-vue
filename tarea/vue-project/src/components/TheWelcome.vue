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
    <template #heading>¿Qué hacemos en isclab?</template>
    <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>
    Desarrollamos aplicaciones con fines de práctica, investigación y responsabilidad social.

Buscamos el desarrollo de nuestros estudiantes a través de la creación de proyectos que sean útiles a la sociedad.

¿Tienes un proyecto en mente? Compártelo con nosotros y buscaremos la manera de ayudarte.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>¿pueden crear un sitio web gratuito para mi proyecto? </template>
    La respuesta corta es sí.

Claro que necesitamos saber en qué consiste el sitio que necesitas y tu historia para valorar el apoyo gratuito en la creación y publicación de tu sitio
  
    <br />

     <code></code>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>¿Qué clase de proyectos realizamos?</template>

    Nuestro laboratorio está pensado para programadores por lo que los productos que creamos se categorizan como software.

El software puede encajar en alguna de estas posibilidades:
    
  </WelcomeItem>

  
</template>
