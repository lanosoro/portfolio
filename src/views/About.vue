<template>
  <div class="help">
     <v-list class="list">
         <v-list-tile
         v-for="link in links"
         :key="link.text" :to="link.route"
         >
          <v-list-tile-title id="tile" >{{link.text}}</v-list-tile-title>
         </v-list-tile>
       </v-list>
       <section id="container">
         <div class="container">
  <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/123941/meat.jpg" alt="Avatar" height="590px" class="image">
  <div class="overlay">
    <div class="text">Hello World</div>
  </div>
</div>
			<div class="thumbnail"
				data-title="Bacon"
				data-description="Bacon ipsum dolor amet filet mignon alcatra short ribs, sausage shoulder tail biltong rump chicken ground round ham hock porchetta tri-tip. Boudin bresaola andouille, leberkas pork ball tip turducken beef ribs">
				<img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/123941/meat.jpg" alt="Meat" width="300">
			</div>
		</section>
  </div>
</template>

<script>
export default {
   data: () => ({
      links: [
        {text:'Pharmaceuticals', route:'/'},
        {text:'medical', route:'photos'},
        {text:'About',route:"/about"},
        {text:'Instagram',route:"whatsapp"},
        {text:'More'},
        {text:'About',route:"/about"},
        {text:'About',route:"/about"},
        {text:'log out',route:'/'}
      ],
     
    }),
}
</script>

<style>
*, *:after, *:before {
	box-sizing: border-box;
}
h1 {
	font-family: Merriweather, serif;
	margin: 0 0 50px;
	cursor: default;
}
#container {
	width: 300px;
	margin: 0 auto;
}



.container {
  position: relative;
  width: 50%;
}

.image {
  display: block;
  width: 100%;
  height: auto;
}

.overlay {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  height: 100%;
  width: 100%;
  opacity: 0;
  transition: .5s ease;
  background-color: #008CBA;
}

.container:hover .overlay {
  opacity: 1;
}

.text {
  color: white;
  font-size: 20px;
  position: absolute;
  top: 50%;
  left: 50%;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  text-align: center;
}

.thumbnail {
	-webkit-backface-visibility: hidden;
	display: inline-block;
	position: relative;
	margin: 0 auto;
	overflow: hidden;
	background: #000;
	box-shadow: 0 15px 50px rgba(0,0,0,.5);
}
.thumbnail img {
	display: block;
	max-width: 100%;
	transition: opacity .2s ease-in-out;
}
.thumbnail:hover img {
	opacity: .5;
}
.thumbnail::after,
.thumbnail::before {
	position: absolute;
	z-index: 1;
	width: 100%;
	height: 50%;
	transition: transform .4s ease-out;
	color: #fff;
}
.thumbnail::after {
	content: attr(data-title);
	top: 0;
	padding-top: 55px;
	transform: translateY(-100%) scale(.8);
	background: rgba(0,0,0,.4);
	font-size: 3.5rem;
	font-weight: 300;
	font-family: Merriweather, serif;
	text-align: center;
}
.thumbnail::before {
	content: attr(data-description) "…";
	top: 50%;
	padding: 20px;
	transform: translateY(100%) scale(.8);
	background: rgba(107,38,68,.6);
	-webkit-backdrop-filter: blur(10px);
	backdrop-filter: blur(10px);
	color: #f1f1f1;
	font-size: 1.5rem;
}
.thumbnail:hover::after,
.thumbnail:hover::before {
	transform: translateY(0%) scale(1);
}
.help{
  width: 100%;
  background: lightcoral;
  height: 100%;
  font-family: 'comfortaa';
  align-content: center;
  
}
.list{
   width: 100%;
   display: flex;
   flex-direction: row;
   flex-wrap: wrap;
   top: 0;
   position: relative;
   align-content: center;
   align-items: center;
   justify-content: center;
}
#tile{
  padding:30px 30px;
  cursor: pointer;
  background: blue;
  margin: 20px;
  position: relative;
  top: calc(10% - 345px);
  height: 100px;
  width: 300px;
  color: white;
  border-radius: 8px;
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;

}
</style>