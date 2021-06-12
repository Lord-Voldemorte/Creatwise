#Creatwise
<!DOCTYPE html>
<html>

<head>
	<title>Creatwise</title>

	<!-- Import bootstrap cdn -->
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css"
		integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
	<link rel="stylesheet" href="bootstrap/dist/css/bootstrap.css">
	<script src="node_modules/jquery/dist/jquery.js"></script>
	<script src="node_modules/bootstrap/dist/js/bootstrap.bundle.js"></script>

	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"
		integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w=="
		crossorigin="anonymous" referrerpolicy="no-referrer" />

	<!-- Import jquery cdn -->
	<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"
		integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous">
	</script>

	<!-- Import popper.js cdn -->
	<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"
		integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous">
	</script>

	<!-- Import javascript cdn -->
	<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"
		integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous">
	</script>
	<script>
		{
			function CreateClick() {
				document.getElementById("name").innerHTML = document.getElementById("txtName").value;
				document.getElementById("s_date").innerHTML = document.getElementById("txtStart").value;
				document.getElementById("e_date").innerHTML = document.getElementById("txtEnd").value;
				document.getElementById("weeks").innerHTML = document.getElementById("txtWeeks").value;
			}

			function navTeam() {
				var x = document.getElementById("side_nav");
				if (x.style.display === "none") {
					x.style.display = "block";
				} else {
					x.style.display = "none";
				}
			}

			function Tac() {
				var x = document.getElementById("tac");
				if (x.style.display === "none") {
					x.style.display = "block";
				} else {
					x.style.display = "none";
				}
			}

			function Dashboard() {
				var x = document.getElementById("dashboard");
				if (x.style.display === "none") {
					x.style.display = "block";
				} else {
					x.style.display = "none";
				}
			}

			function Tactics() {
				var x = document.getElementById("tactics");
				if (x.style.display === "none") {
					x.style.display = "block";
				} else {
					x.style.display = "none";
				}
			}

			function Team() {
				var x = document.getElementById("team");
				if (x.style.display === "none") {
					x.style.display = "block";
				} else {
					x.style.display = "none";
				}
			}

			function Schedule() {
				var x = document.getElementById("schedule");
				if (x.style.display === "none") {
					x.style.display = "block";
				} else {
					x.style.display = "none";
				}
			}

			function Plans() {
				var x = document.getElementById("plans");
				if (x.style.display === "none") {
					x.style.display = "block";
				} else {
					x.style.display = "none";
				}
			}

			function Metrics() {
				var x = document.getElementById("metrics");
				if (x.style.display === "none") {
					x.style.display = "block";
				} else {
					x.style.display = "none";
				}
			}

			function Customization() {
				var x = document.getElementById("customization");
				if (x.style.display === "none") {
					x.style.display = "block";
				} else {
					x.style.display = "none";
				}
			}
		}
	</script>

	<!-- CSS stylesheet -->
	<style type="text/css">
		html,
		body {
			height: 100%;
		}

		#side_nav {
			height: auto;
			max-height: 100%;
			background: rgb(12, 145, 12);
			color: black;
			padding: 150px 20px 105px 10px;
		}

		.fa-head-side-virus {
			font-size: 30px;
		}

		.col-2 a {
			color: white;
			text-decoration-line: none;
		}

		.col-2 a:hover {
			color: wheat;
		}

		nav {
			font-weight: bold;
		}

		#menu1 {
			border: none;
			display: flex;
		}

		#day1,
		#day2,
		#day3,
		#day4,
		#day5,
		#day6,
		#day7 {
			background-color: white;
			color: gray;
			margin-left: 15px;
			padding: 5px;
			width: 150px;
		}

		.b-icons {
			display: flex;
			align-self: flex-end;
			justify-content: right;
			flex-direction: column;
		}
	</style>
</head>

<body>
	<div class="container-fluid h-100">

		<!-- h-100 takes the full height
				of the container-->
		<div class="row h-100">
			<div class="col-2" id="side_nav">
				<a href="#" onclick="Tac()"><i class="fas fa-head-side-virus">&nbsp;&nbsp;</i>Tac-Tic-Tec</a><br />
				<br />
				<!-- Navigation links in sidebar-->
				<a href="#" onclick="Dashboard()"><i class="fas fa-chart-pie">&nbsp;&nbsp;&nbsp;</i>Dashboard</a><br />
				<br />
				<a href="#" onclick="Tactics()"><i class="fas fa-chess-board">&nbsp;&nbsp;&nbsp;</i>Tactics Vault</a><br />
				<br />
				<a href="#" onclick="Team()"><i class="fas fa-users">&nbsp;&nbsp;</i>Teams</a><br />
				<br />
				<a href="#" onclick="Schedule()"><i class="fas fa-file-alt">&nbsp;&nbsp;&nbsp;&nbsp;</i>Schedule
					Generator</a><br />
				<br />
				<a href="#" onclick="Plans()"><i class="fas fa-calendar-alt">&nbsp;&nbsp;&nbsp;</i>Weekly Training
					Plans</a><br />
				<br />
				<a href="#" onclick="Metrics()"><i class="fas fa-chart-bar">&nbsp;&nbsp;</i>Team Metrics</a><br />
				<br />
				<a href="#" onclick="Customization()"><i class="fas fa-cog">&nbsp;&nbsp;</i>Customization</a><br />
				<br />
				<div>
					<br><br><br><br><br><br><br><br><br><br>
					<b style="color: rgb(250, 250, 250);">Select Your Team</b><br>
					<div class="btn-group dropup" style="width: 100px;">
						<button type="button" class="btn btn-light dropdown-toggle" data-toggle="dropdown" aria-haspopup="true"
							aria-expanded="false">
							Team Name
						</button>
						<div class="dropdown-menu">
							<a class="dropdown-item" style="color: rgb(81, 218, 81);" href="#!">Team1</a>
							<a class="dropdown-item" style="color: rgb(81, 218, 81);" href="#!">Team2</a>
						</div>
					</div>
				</div>

			</div>
			<div class="col-10" style="padding: 0;">

				<!-- Top navbar -->
				<nav class="navbar navbar-expand-lg
								navbar-light bg-light">
					<a class="navbar-brand" href="#">Creatwise</a>
					<!-- Hamburger button that toggles the navbar-->
					<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup"
						aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
						<span class="navbar-toggler-icon"></span>
					</button>
					<!-- navbar links -->
					<div class="collapse navbar-collapse" id="navbarNavAltMarkup">
						<div class="navbar-nav">
							<a class="nav-item nav-link
								active" href="#" onclick="navTeam()">Team</a>
							<a class="nav-item nav-link" href="#">U23</a>
							<a class="nav-item nav-link" href="#">U19</a>
						</div>
					</div>
				</nav>


				<br>
				<!-- Side-Nav menu's Items -->
				<div>
					<div>
						<div id="tac" class="container-fluid">
							<div class="btn btn-light form-control d-flex" data-toggle="collapse" data-target="#tacData">Tac-Tic-Tec
							</div>
							<div id="tacData" class="collapse">
								<hr>
								<h2>Write your content Here</h2>
							</div>
						</div>
						<br>
						<div>
							<div id="dashboard" class="container-fluid">
								<div class="btn btn-light form-control d-flex" data-toggle="collapse" data-target="#dashboardData">
									Dashboard</div>
								<div id="dashboardData" class="collapse">
									<hr>
									<h2>Write your content Here</h2>
								</div>
							</div>
						</div>
						<br>
						<div>
							<div id="tactics" class="container-fluid">
								<div class="btn btn-light form-control d-flex" data-toggle="collapse" data-target="#tacticsData">
									Tacktics
									Vaults</div>
								<div id="tacticsData" class="collapse">
									<hr>
									<h2>Write your content Here</h2>
								</div>
							</div>
							<br>
							<div>
								<div id="team" class="container-fluid">
									<div class="btn btn-light form-control d-flex" data-toggle="collapse" data-target="#teamData">Team
									</div>
									<div id="teamData" class="collapse">
										<hr>
										<h2>Write your content Here</h2>
									</div>
									<br>
								</div>
								<div id="schedule" class="container-fluid">
									<div class="wts">
										<!-- Contains the main content of the webpage-->
										<div style="padding: 15px; text-align: justify;">
											<button data-toggle="modal" data-target="#createModal" class="btn btn-success"><a href="#"
													style="color: cornsilk; text-decoration: none;">Add New Schedule</a></button>
											<form action="" method="POST">
												<div class="modal fade" id="createModal">
													<div class="modal-dialog">
														<div class="modal-content">
															<div class="modal-header">
																<h3>Create New Schedule</h3>
																<button data-dismiss="modal" class="btn btn-close"></button>
															</div>
															<div class="modal-body">
																<dl>
																	<dt>Schedule Name</dt>
																	<dd>
																		<input type="text" id="txtName" class="form-control">
																	</dd>
																	<dt>Start Date</dt>
																	<dd>
																		<input type="date" id="txtStart" class="form-control">
																	</dd>
																	<dt>End Date</dt>
																	<dd>
																		<input type="date" id="txtEnd" class="form-control">
																	</dd>
																	<dt>Enter No. of Weeks</dt>
																	<dd>
																		<input type="number" id="txtWeeks" class="form-control">
																	</dd>
																</dl>
															</div>
															<div class="modal-footer">
																<button data-dismiss="modal" class="btn btn-danger form-control">Close</button>
																<button data-dismiss="modal" onclick="CreateClick()"
																	class="btn btn-success form-control" data-toggle="modal" data-target="#order"><a
																		style="color: white;">Create</a></button>
															</div>
														</div>
													</div>
												</div>
											</form>
										</div>
										<div class="accordion" id="parent">
											<button type="button" class="btn btn-light form-control d-flex" data-toggle="collapse"
												data-target="#collapse1" style="height: max-content; padding: 5px;">Winter Training Schedule
												<br>4 weeks | 12 Sessions
											</button>
											<hr>
											<div class="collapse" id="collapse1" data-parent="#parent">
												<div class="d-flex justify-content-between">
													<div id="cl1" class="d-flex ">
														<div class="p-3">
															<div>START DATE</div>
															<h6>25 January 2020</h6>
														</div>
														<div class="p-3 pl-5">
															<div>END DATE</div>
															<h6>19 February 2020</h6>
														</div>
													</div>
													<div>
														<button class="btn btn-success text-center text-white pl-4 pr-4 m-3">Update</button>
													</div>
												</div>
												<div>
													<button id="day1"><input type="radio" name="days" value="SUNDAY">&nbsp;&nbsp;SUNDAY</button>
													<button id="day2"><input type="radio" name="days" value="MONDAY">&nbsp;&nbsp;MONDAY</button>
													<button id="day3"><input type="radio" name="days" value="TUESDAY">&nbsp;&nbsp;TUESDAY</button>
													<button id="day4"><input type="radio" name="days"
															value="WEDNESDAY">&nbsp;&nbsp;WEDNESDAY</button>
													<button id="day5"><input type="radio" name="days"
															value="THURSDAY">&nbsp;&nbsp;THURSDAY</button>
													<button id="day6"><input type="radio" name="days" value="FRIDAY">&nbsp;&nbsp;FRIDAY</button>
													<button id="day7"><input type="radio" name="days"
															value="SATURDAY">&nbsp;&nbsp;SATURDAY</button>
												</div>
											</div>


											<br>
											<button type="button" class="btn btn-light form-control d-flex" data-toggle="collapse"
												data-target="#collapse2" style="height: max-content; padding: 5px;">Winter Training Schedule
												<br>4 weeks | 12 Sessions
											</button>

											<hr>
											<div class="collapse" id="collapse2" data-parent="#parent">
												<div class="d-flex justify-content-between">
													<div id="cl1" class="d-flex ">
														<div class="p-3">
															<div>START DATE</div>
															<h6>25 January 2020</h6>
														</div>
														<div class="p-3 pl-5">
															<div>END DATE</div>
															<h6>19 February 2020</h6>
														</div>
													</div>
													<div>
														<button class="btn btn-success text-center text-white pl-4 pr-4 m-3">Update</button>
													</div>
												</div>
												<div>
													<button id="day1"><input type="radio" name="days" value="SUNDAY">&nbsp;&nbsp;SUNDAY</button>
													<button id="day2"><input type="radio" name="days" value="MONDAY">&nbsp;&nbsp;MONDAY</button>
													<button id="day3"><input type="radio" name="days" value="TUESDAY">&nbsp;&nbsp;TUESDAY</button>
													<button id="day4"><input type="radio" name="days"
															value="WEDNESDAY">&nbsp;&nbsp;WEDNESDAY</button>
													<button id="day5"><input type="radio" name="days"
															value="THURSDAY">&nbsp;&nbsp;THURSDAY</button>
													<button id="day6"><input type="radio" name="days" value="FRIDAY">&nbsp;&nbsp;FRIDAY</button>
													<button id="day7"><input type="radio" name="days"
															value="SATURDAY">&nbsp;&nbsp;SATURDAY</button>
												</div>
											</div>

											<br>
											<button type="button" class="btn btn-light form-control d-flex" data-toggle="collapse"
												data-target="#collapse3" style="height: max-content; padding: 5px;">Winter Training Schedule
												<br>4 weeks | 12 Sessions
											</button>

											<hr>
											<div class="collapse" id="collapse3" data-parent="#parent">
												<div class="d-flex justify-content-between">
													<div id="cl1" class="d-flex ">
														<div class="p-3">
															<div>START DATE</div>
															<h6>25 January 2020</h6>
														</div>
														<div class="p-3 pl-5">
															<div>END DATE</div>
															<h6>19 February 2020</h6>
														</div>
													</div>
													<div>
														<button class="btn btn-success text-center text-white pl-4 pr-4 m-3">Update</button>
													</div>
												</div>
												<div>
													<button id="day1"><input type="radio" name="days" value="SUNDAY">&nbsp;&nbsp;SUNDAY</button>
													<button id="day2"><input type="radio" name="days" value="MONDAY">&nbsp;&nbsp;MONDAY</button>
													<button id="day3"><input type="radio" name="days" value="TUESDAY">&nbsp;&nbsp;TUESDAY</button>
													<button id="day4"><input type="radio" name="days"
															value="WEDNESDAY">&nbsp;&nbsp;WEDNESDAY</button>
													<button id="day5"><input type="radio" name="days"
															value="THURSDAY">&nbsp;&nbsp;THURSDAY</button>
													<button id="day6"><input type="radio" name="days" value="FRIDAY">&nbsp;&nbsp;FRIDAY</button>
													<button id="day7"><input type="radio" name="days"
															value="SATURDAY">&nbsp;&nbsp;SATURDAY</button>
												</div>
											</div>

											<br>
											<button type="button" class="btn btn-light form-control d-flex" data-toggle="collapse"
												data-target="#collapse4" style="height: max-content; padding: 5px;">Winter Training Schedule
												<br>4 weeks | 12 Sessions
											</button>

											<hr>
											<div class="collapse" id="collapse4" data-parent="#parent">
												<div class="d-flex justify-content-between">
													<div id="cl1" class="d-flex ">
														<div class="p-3">
															<div>START DATE</div>
															<h6>25 January 2020</h6>
														</div>
														<div class="p-3 pl-5">
															<div>END DATE</div>
															<h6>19 February 2020</h6>
														</div>
													</div>
													<div>
														<button class="btn btn-success text-center text-white pl-4 pr-4 m-3">Update</button>
													</div>
												</div>
												<div>
													<button id="day1"><input type="radio" name="days" value="SUNDAY">&nbsp;&nbsp;SUNDAY</button>
													<button id="day2"><input type="radio" name="days" value="MONDAY">&nbsp;&nbsp;MONDAY</button>
													<button id="day3"><input type="radio" name="days" value="TUESDAY">&nbsp;&nbsp;TUESDAY</button>
													<button id="day4"><input type="radio" name="days"
															value="WEDNESDAY">&nbsp;&nbsp;WEDNESDAY</button>
													<button id="day5"><input type="radio" name="days"
															value="THURSDAY">&nbsp;&nbsp;THURSDAY</button>
													<button id="day6"><input type="radio" name="days" value="FRIDAY">&nbsp;&nbsp;FRIDAY</button>
													<button id="day7"><input type="radio" name="days"
															value="SATURDAY">&nbsp;&nbsp;SATURDAY</button>
												</div>
											</div>

											<br>
											<button type="button" class="btn btn-light form-control d-flex" data-toggle="collapse"
												data-target="#collapse5" style="height: max-content; padding: 5px;">Winter Training Schedule
												<br>4 weeks | 12 Sessions
											</button>

											<hr>
											<div class="collapse" id="collapse5" data-parent="#parent">
												<div class="d-flex justify-content-between">
													<div id="cl1" class="d-flex ">
														<div class="p-3">
															<div>START DATE</div>
															<h6>25 January 2020</h6>
														</div>
														<div class="p-3 pl-5">
															<div>END DATE</div>
															<h6>19 February 2020</h6>
														</div>
													</div>
													<div>
														<button class="btn btn-success text-center text-white pl-4 pr-4 m-3">Update</button>
													</div>
												</div>
												<div>
													<button id="day1"><input type="radio" name="days" value="SUNDAY">&nbsp;&nbsp;SUNDAY</button>
													<button id="day2"><input type="radio" name="days" value="MONDAY">&nbsp;&nbsp;MONDAY</button>
													<button id="day3"><input type="radio" name="days" value="TUESDAY">&nbsp;&nbsp;TUESDAY</button>
													<button id="day4"><input type="radio" name="days"
															value="WEDNESDAY">&nbsp;&nbsp;WEDNESDAY</button>
													<button id="day5"><input type="radio" name="days"
															value="THURSDAY">&nbsp;&nbsp;THURSDAY</button>
													<button id="day6"><input type="radio" name="days" value="FRIDAY">&nbsp;&nbsp;FRIDAY</button>
													<button id="day7"><input type="radio" name="days"
															value="SATURDAY">&nbsp;&nbsp;SATURDAY</button>
												</div>
											</div>

											<br>
											<button type="button" class="btn btn-light form-control d-flex" data-toggle="collapse"
												data-target="#collapse6" style="height: max-content; padding: 5px;">Winter Training Schedule
												<br>4 weeks | 12 Sessions
											</button>

											<hr>
											<div class="collapse" id="collapse6" data-parent="#parent">
												<div class="d-flex justify-content-between">
													<div id="cl1" class="d-flex ">
														<div class="p-3">
															<div>START DATE</div>
															<h6>25 January 2020</h6>
														</div>
														<div class="p-3 pl-5">
															<div>END DATE</div>
															<h6>19 February 2020</h6>
														</div>
													</div>
													<div>
														<button class="btn btn-success text-center text-white pl-4 pr-4 m-3">Update</button>
													</div>
												</div>
												<div>
													<button id="day1"><input type="radio" name="days" value="SUNDAY">&nbsp;&nbsp;SUNDAY</button>
													<button id="day2"><input type="radio" name="days" value="MONDAY">&nbsp;&nbsp;MONDAY</button>
													<button id="day3"><input type="radio" name="days" value="TUESDAY">&nbsp;&nbsp;TUESDAY</button>
													<button id="day4"><input type="radio" name="days"
															value="WEDNESDAY">&nbsp;&nbsp;WEDNESDAY</button>
													<button id="day5"><input type="radio" name="days"
															value="THURSDAY">&nbsp;&nbsp;THURSDAY</button>
													<button id="day6"><input type="radio" name="days" value="FRIDAY">&nbsp;&nbsp;FRIDAY</button>
													<button id="day7"><input type="radio" name="days"
															value="SATURDAY">&nbsp;&nbsp;SATURDAY</button>
												</div>
											</div>
										</div>
									</div>
								</div>
							</div>
							<br>
							<div>
								<div id="plans" class="container-fluid">
									<div class="btn btn-light form-control d-flex" data-toggle="collapse" data-target="#plansData">Weekly
										Training Plans</div>
									<div id="plansData" class="collapse">
										<hr>
										<h2>Write your content Here</h2>
									</div>
								</div>
								<br>
								<div>
									<div id="metrics" class="container-fluid">
										<div class="btn btn-light form-control d-flex" data-toggle="collapse" data-target="#metricsData">
											Team
											Metrics</div>
										<div id="metricsData" class="collapse">
											<hr>
											<h2>Write your content Here</h2>
										</div>
									</div>
									<br>
									<div>
										<div id="customization" class="container-fluid">
											<div class="btn btn-light form-control d-flex" data-toggle="collapse"
												data-target="#customizationData">
												Customization</div>
											<div id="customizationData" class="collapse">
												<hr>
												<h2>Write your content Here</h2>
											</div>
										</div>
										<!-- Validation Table -->
										<div class="modal" id="order">
											<div class="modal-dialog">
												<div class="modal-content">
													<div class="modal-header">
														<h2 class=" text-info">Customer Info</h2>
													</div>
													<div class="modal-body" style="background-image: none;">
														<table class="table table-hover" style="font-weight: bolder;">
															<tr>
																<td>Schedule Name</td>
																<td id="name"></td>
															</tr>
															<tr>
																<td>Start Date</td>
																<td id="s_date"></td>
															</tr>
															<tr>
																<td>End Date</td>
																<td id="e_date"></td>
															</tr>
															<tr>
																<td>No. of weeks</td>
																<td id="weeks"></td>
															</tr>
														</table>
													</div>
													<div class="modal-footer">
														<button class="btn btn-success" data-dismiss="modal"> Ok</button>
														<button class="btn btn-secondary" data-dismiss="modal">cancel</button>
													</div>
												</div>
</body>

</html>
