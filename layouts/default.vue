<template>
    <div>
        <div class="fixed z-50 top-0">
            <CoreNavbar />
        </div>
        <div class="relative top-[71px] md:top-[89px]">
            <slot />
            <CoreFooter />
        </div>
    </div>
</template>