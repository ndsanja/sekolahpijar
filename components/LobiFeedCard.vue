<script>
export default {
  data: () => ({
    //
  }),
}
</script>
<template>
  <v-card class="mx-auto w full rounded-lg border">
    <v-card-actions>
      <v-list-item class="w-100">
        <template v-slot:prepend>
          <v-avatar color="grey-darken-3"
            image="https://avataaars.io/?avatarStyle=Transparent&topType=ShortHairShortCurly&accessoriesType=Prescription02&hairColor=Black&facialHairType=Blank&clotheType=Hoodie&clotheColor=White&eyeType=Default&eyebrowType=DefaultNatural&mouthType=Default&skinColor=Light"></v-avatar>
        </template>

        <v-list-item-title style="font-size: medium;">Nila Dwi Sanja</v-list-item-title>

        <v-list-item-subtitle style="font-size: x-small;">56 menit yang lalu</v-list-item-subtitle>

        <template v-slot:append>
          <div class="justify-self-end">
            <v-icon class="me-1" style="font-size: larger;" icon="mdi-dots-vertical"></v-icon>
          </div>
        </template>
      </v-list-item>
    </v-card-actions>

    <div class="mx-4 pt-2">
      <div class="rounded-xl bg-indigo-500 aspect-video">
      </div>
    </div>

    <v-card-text class="text-p py-2 mx-4">
      "Turns out semicolon-less style is easier and safer in TS because most gotcha edge cases are type invalid as well."
    </v-card-text>


    <v-card-actions>
      <v-list-item class="w-100" style="font-size: medium;">
        <template v-slot:prepend>
          <v-icon class="me-1" style="font-size: medium;" icon=" mdi-heart"></v-icon>
          <span class="subheading me-2" style="font-size: small;">256</span>
          <span class="me-1" style="font-size: medium;">·</span>
          <v-icon class="me-1" style="font-size: medium;" icon="mdi-share-variant"></v-icon>
          <span class="subheading" style="font-size: small;">45</span>
        </template>


        <template v-slot:append>
          <div class="justify-self-end">
            <span class="subheading me-2" style="font-size: small;">120</span>
            <v-icon class="me-1" icon="mdi-chat-outline" style="font-size: medium;"></v-icon>
          </div>
        </template>
      </v-list-item>
    </v-card-actions>
  </v-card>
</template>
