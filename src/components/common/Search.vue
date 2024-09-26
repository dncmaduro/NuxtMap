<template>
  <div>
    <UInput placeholder="Search..." class="w-[400px] relative" size="lg" :ui="{rounded: 'rounded-full', icon: {trailing: {pointer: ''}}}">
      <template #trailing>
        <UButton size="xs" class="rounded-full">
          Search
        </UButton>
      </template>
    </UInput>
  </div>
</template>