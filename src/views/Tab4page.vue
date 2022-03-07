<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Tab 4</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 3</ion-title>
        </ion-toolbar>
      </ion-header>

<ion-content fullscreen>
        <ion-card>
          <img src="https://scontent.fphs2-1.fna.fbcdn.net/v/t39.30808-1/261337840_3130924460486859_3077857859404906791_n.jpg?stp=dst-jpg_p240x240&_nc_cat=107&ccb=1-5&_nc_sid=7206a8&_nc_eui2=AeFouHockH-9u9E8WzZzdZiYJD519OZLfPwkPnX05kt8_KsDiZzENoyjWW7GEwu0u0hqr0em9US6o0nFL4LFNcAe&_nc_ohc=wJkvOvOLr6QAX_7eGRP&_nc_ht=scontent.fphs2-1.fna&oh=00_AT-gVqQCgQbVzcg_VmJpxny0SggBLuu_qfw9fSHynmr9qQ&oe=622B2CD8" />
          <ion-card-header>
            
            <ion-card-title>วรชิต โต๊ะโต</ion-card-title>
          </ion-card-header>
          <ion-card-content>
            รหัสนักศึกษา : 62442206008-4
<ion-card-subtitle>เบอร์โทร :0956843881</ion-card-subtitle>
           

          </ion-card-content>
        </ion-card>
      </ion-content>
      
      <ExploreContainer name="Tab 4 page" />
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';


export default defineComponent({
  name: 'Tab3Page',
  components: { IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
});


</script>