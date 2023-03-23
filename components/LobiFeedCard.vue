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

        <v-list-item-title class="!text-sm">Nila Dwi Sanja</v-list-item-title>

        <v-list-item-subtitle class="!text-[10px]">56 menit yang lalu</v-list-item-subtitle>

        <template v-slot:append>
          <div class="!self-end">
            <v-icon class="!mr-1 !text-base" icon="mdi-dots-vertical"></v-icon>
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
      <v-list-item class="w-100 !text-base">
        <template v-slot:prepend>
          <v-icon class=" !mr-1 !text-base" icon=" mdi-heart"></v-icon>
          <span class="!mr-2 !text-xs">256</span>
          <span class="!mr-1 !text-base">·</span>
          <v-icon class=" !mr-1 !text-base" icon=" mdi-share-variant"></v-icon>
          <span class="!text-xs">45</span>
        </template>


        <template v-slot:append>
          <div class="!self-end">
            <span class="!mr-2 !text-xs">120</span>
            <v-icon class="!mr-1 !text-base" icon="mdi-chat-outline"></v-icon>
          </div>
        </template>
      </v-list-item>
    </v-card-actions>
  </v-card>
</template>
