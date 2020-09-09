<template>
  <div class="hello">
    <header>
			<nav>   
			<ul id="topmenu">
        v-bind:src="C:\Users\islam\registration\src\assets\logo.png"
        <button class="sidebar__toggle" data-sidebar-toggle=""></button>
				<li >ГЛАВНАЯ</li>
				<li >МОДУЛИ</li>
				<li >КЛИНИКИ</li>
				<li >КОНТАКТЫ</li>
        <li >8 800 000 00 00</li>
			</ul>
			</nav>
		</header>
    <h1>{{ msg }}</h1>
  </div>
 
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
header {
  width:100%;
    color:#fcfcfc;
    font-size: 15pt;
    background: #850985;
    display: block;
    position: relative;
    z-index: 2;
}
header {
    display: block;
}
ul {
  margin-left:50%;
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
.sidebar__toggle:before {
    font-size: 22px;
}
.sidebar .map, .sidebar .sidebar__toggle {
    position: absolute;
    top: 12px;
    left: 100%;
    margin-left: 19px;
    width: 44px;
    height: 44px;
    border-radius: 50%;
    cursor: pointer;
}
</style>
