<template>
    <div class="loader-wrap d-flex align-items-center justify-content-center flex-wrap">
        <svg width="200px" height="200px" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"
             preserveAspectRatio="xMidYMid" class="lds-ripple">
            <circle cx="50" cy="50" r="26.5737" fill="none"
                    stroke="#f05125" stroke-width="2">
                <animate attributeName="r" calcMode="spline" values="0;40" keyTimes="0;1" dur="1"
                         keySplines="0 0.2 0.8 1"
                         begin="-0.5s" repeatCount="indefinite"></animate>
                <animate attributeName="opacity" calcMode="spline" values="1;0" keyTimes="0;1" dur="1"
                         keySplines="0.2 0 0.8 1" begin="-0.5s" repeatCount="indefinite"></animate>
            </circle>
            <circle cx="50" cy="50" r="2.70736" fill="none"
                    stroke="#fdb813" stroke-width="2">
                <animate attributeName="r" calcMode="spline" values="0;40" keyTimes="0;1" dur="1"
                         keySplines="0 0.2 0.8 1"
                         begin="0s" repeatCount="indefinite"></animate>
                <animate attributeName="opacity" calcMode="spline" values="1;0" keyTimes="0;1" dur="1"
                         keySplines="0.2 0 0.8 1" begin="0s" repeatCount="indefinite"></animate>
            </circle>
        </svg>
    </div>
</template>

<script>
    export default {}
</script>

<style>

</style>