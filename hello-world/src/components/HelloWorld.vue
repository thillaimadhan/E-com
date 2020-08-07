<template>

	<div class="hello">
	
			<form action="http://localhost:3000/order" method="POST" enctype="application/x-www-form-urlencoded">

					<button type="submit" class="btn btn-default"> <svg width="1em" height="1em" viewBox="0 0 16 16" class="bi bi-cart-fill" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
  <path fill-rule="evenodd" d="M0 1.5A.5.5 0 0 1 .5 1H2a.5.5 0 0 1 .485.379L2.89 3H14.5a.5.5 0 0 1 .491.592l-1.5 8A.5.5 0 0 1 13 12H4a.5.5 0 0 1-.491-.408L2.01 3.607 1.61 2H.5a.5.5 0 0 1-.5-.5zM5 12a2 2 0 1 0 0 4 2 2 0 0 0 0-4zm7 0a2 2 0 1 0 0 4 2 2 0 0 0 0-4zm-7 1a1 1 0 1 0 0 2 1 1 0 0 0 0-2zm7 0a1 1 0 1 0 0 2 1 1 0 0 0 0-2z"/>
</svg>Check Out Cart</button>
		<h1>{{ msg }}</h1><br>
		
			<div class="form-group">
				<div class="container-fluid">
					<!-- Control the column width, and how they should appear on different devices -->
					<div class="row">
						<div class="col-sm-4">
							<div class="card" style=" "> <img class="card-img-top" src="https://www.liveeatlearn.com/wp-content/uploads/2018/04/carrot-on-white-vert.jpg" alt="Card image" style="width:50%">
								<div class="card-body">
									<h4 class="card-title">Kraft Carrot</h4>
									<p class="card-text">Carrots are a good source of several vitamins and minerals, especially biotin, potassium</p>
									<input type="number" id="name" name="item1"  size="1">KG
                                    <input type="hidden" name="itemid1" value="carrot">

									<br>
									<br> </div>
							</div>
						</div>
						<div class="col-sm-4">
							<div class="card" style=" "> <img class="card-img-top" src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/47/TomategelbFleisch.jpg/220px-TomategelbFleisch.jpg" alt="Card image" style="width:50%">
								<div class="card-body">
									<h4 class="card-title">Cherry Tomatoes</h4>
									<p class="card-text"> Bright and sweet, they have a thin, snappy peel and a very juicy center</p>
                  <input type="hidden" name="itemid2" value="tomoto">
									<input type="number" id="name" name="item2" maxlength="4" size="4">KG
									<br>
									<br> </div>
							</div>
						</div>
						<div class="col-sm-4">
							<div class="card" style=" "> <img class="card-img-top" src="https://upload.wikimedia.org/wikipedia/commons/6/63/Hillview_Farms_white_potatoes.jpg" alt="Card image" style="width:50%">
								<div class="card-body">
									<h4 class="card-title">Russet Potatoes</h4>
									<p class="card-text">Excellent source of vitamin C, Potassium, fibre, B vitamins copper, tryptophan, manganese and even lutein</p>
                     <input type="hidden" name="itemid3" value="pototo">

									<input type="number" id="name" name="item3" maxlength="4" size="4">KG
									<br>
									<br> </div>
							</div>
						</div>
					</div>
				</div>
			
			</div>
		</form>
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
h3 {
	margin: 40px 0 0;
}

ul {
	list-style-type: none;
	padding: 0;
}

li {
	display: inline-block;
	margin: 0 10px;
}

a {
	color: #42b983;
}
input {
  width: 10%;
}
</style>