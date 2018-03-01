<template>
    <div class="hero">
	<h1>Simplify Your Life</h1>
	<img v-bind:src="imagePath"/>
  <p>Photo by Mandy Lackey.</p>
  <p>Found on <a href="https://www.flickr.com/photos/mandaloo/2991393021/in/photolist-5ykEVK-a1dQ5j-pg8vHM-bJLZuK-emZb16-otFEZL-eGBTvs-5ZRujz-4Friy2-5gwhuM-4kvmDf-a1aYcB-7nQMk4-nJhCGV-2AJCmZ-6c2Km5-iv1oUU-dUWJm7-9ynKa7-9Jf4ye-bVEq7w-98RBJW-fx5784-5u35sM-nNY4AZ-aaB5kp-9WSgK1-9M2qpa-awunPs-7QEwqb-ajcEiw-faCDCW-eifxBD-oynn8k-dVu1Kv-94yNwG-ELauJx-pcG7m-2j2Xv8-m4arbk-5yiSZV-6PKfX8-5Gky7r-6UV2cZ-n6bTjZ-j3cNpt-dbK4TY-8waXsh-dpoamB-e9bKyf">Flickr</a></p>
    </div>
</template>

<script>
 export default {
     name: 'HomePage',
     data () {
    	 return {
    	     imagePath: '/static/candy1.png'
	     }
     }
 }
</script>

<style scoped>
 body {
     padding: 0px;
     margin: 0px;
 }
 .hero {
     text-align: center;
 }
 h1 {
     font-size: 2.5em;
     letter-spacing: .2rem;
     color: #999;
     margin-bottom: 2px;
 }
 img {
     width: 100%;
 }
</style>
