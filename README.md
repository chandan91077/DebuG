<!DOCTYPE html>
<html lang="en">

<head>
	<link rel="stylesheet" href="HHH.css">
</head>

<body>
	<header class="header-fixed">

		<div class="header-limiter">

			<h1><a href="#">Product Launch <span>Event</span> Management</a></h1>

			<nav>
				<a href="Home.html">Home</a>
				<a href="Event">Event</a>
				<a href="about.html">About</a>
				<a href="sign in.html">Sign In</a>
			</nav>

		</div>

	</header>


	<section>
		<div class="leftBox">
			<div class="content">
				<h1>
					Events and Shows
				</h1>
				<p>
					An event and show website for product launches
					requires careful consideration of various elements
					to ensure its success. It should outline the requirements
					for hosting such events, including venue specifications,
					technical setup, and audience engagement strategies.
					Additionally, the website should highlight features such
					as seamless registration, dynamic content presentation,
					and interactive communication channels. Encouraging innovation
					and adding extra features can enhance user experience and make
					the event more memorable. Ultimately, the website should be designed
					to achieve its objectives of promoting the product effectively, generating
					excitement among attendees, and fostering meaningful connections between
					the brand and its audience.

				</p>
			</div>
		</div>
		<div class="events">
			<ul>
				<li>
					<div class="time">
						<h2>
							15 <br><span>March</span>
						</h2>
					</div>
					<div class="details">
						<h3>
							Where is the event happening?
						</h3>
						<p>This event is going to happen in LPU
							which is the biggest private university
							in India. We tend to give our best to
							contribute to this event because it will
							make our attendee happy.


						</p>
						<a href="#">View Details</a>
					</div>
					<div style="clear: both;"></div>
				</li>
				<li>
					<div class="time">
						<h2>
							27 <br><span>May</span>
						</h2>
					</div>
					<div class="details">
						<h3>
							Where is the event happening?
						</h3>
						<p>
							Occasion sending off, particularly for item dispatches,
							is an essential second in showcasing system.
							It includes careful preparation, dazzling introductions,
							and consistent execution. From conceptualization to post-occasion
							investigation, everything about.
						</p>
						<a href="#">View Details</a>
					</div>
					<div style="clear:both;"></div>
				</li>
				<li>
					<div class="time">
						<h2>
							12 <br><span>August</span>
						</h2>
					</div>
					<div class="details">
						<h3>
							Where is the event happening?
						</h3>
						<p>
							With the idea of imparting programming
							knowledge, Mr. Sandeep Jain, an IIT
							Roorkee alumnus started a dream,
							Whether programming
							excites you or you feel stifled,
							how to ace data structures and
							algorithms.
						</p>
						<a href="#">View Details</a>
					</div>
					<div style="clear:both;"></div>
				</li>
			</ul>
		</div>
	</section>
	<section class="text-gray-600 body-font">
		<div class="container px-5 py-24 mx-auto">
		  <div class="flex flex-col text-center w-full mb-20">
			<h1 class="sm:text-3xl text-2xl font-medium title-font mb-4 text-gray-900" style="color:white">Every Things is Hard before its Use...!!</h1>
			<p class="lg:w-2/3 mx-auto leading-relaxed text-base" style="color:white;" >It’s not about the event itself; it’s about creating a memorable experience for your audience</p>
		  </div>
		  <div class="row">
			  <div class="column">
				<img src="WhatsApp Image 2024-03-23 at 02.23.15_2b238f88.jpg" alt="Snow" style="width: 90%;">
			  </div>
			  <div class="column">
				<img src="12234.jpg" alt="Forest" style="width: 100%;">
				<h1 style="color:white;">What we've been up to</h1>
			  </div>
			<div class="column">
			
			</div>
			</div>
		</div>
	  </section>
		  <footer>
			  <div class="footer-content">
				  <p>&copy; 2024 Your Website. All rights reserved.</p>
			  </div>
		  </footer>  

	<center>
		<h1 style="color:rgb(50, 121, 21);">Guest of the Event</h1>
		<hr>

		<!-- First member of the team -->
		<div class="row">
			<div class="column" id="gfg">
				<div class="card">
					

					<div class="container">
						<h2 style="color:white;">Elon Musk</h2><img class="avatar"  src="elon-mus.jpg" alt="avatar" >
						<p style="color:white;">CEO & Founder</p>
						<p style="color:white;">
							Feel your customer make
							them happy
						</p>

						<button class="button">
							View
						</button>
					</div>
				</div>
			</div>
		</div>

		<!-- Other members of the team -->



		<div class="column">
			<div class="card">
				
				<div class="container">
					
					<h2 style="color:white;">Mike Tyson</h2><img class="avatar"  src="123.jpg" alt="avatar" >
					<p style="color:white;">Marketing Head</p>
					<p style="color:white;">
					
						Sell the product like
						Greatest Mary 
					</p>
					<button class="button">
						View
					</button>
				</div>
			</div>
		</div>
		</div>
	</center>

</body>

</html>


.header-fixed {
    background-color: #032552ee;
    box-shadow: 0 1px 1px #ccc;
    padding: 20px 40px;
    height: 80px;
    color: #ffffff;
    box-sizing: border-box;
    top: -100px;
    -webkit-transition: top 0.3s;
    transition: top 0.3s;
}

.header-fixed .header-limiter {
    max-width: 1200px;
    text-align: center;
    margin: 0 auto;
}

.header-fixed .header-limiter h1 {
    float: left;
    font: normal 28px Cookie, Arial, Helvetica, sans-serif;
    line-height: 40px;
    margin: 0;
}

.header-fixed .header-limiter h1 span {
    color: #5383d3;
}

.header-fixed .header-limiter a {
    color: #ffffff;
    text-decoration: none;
}

.header-fixed .header-limiter nav {
    font: 16px Arial, Helvetica, sans-serif;
    line-height: 40px;
    float: right;
}

.header-fixed .header-limiter nav a {
    display: inline-block;
    padding: 0 5px;
    text-decoration: none;
    color: #ffffff;
    opacity: 0.9;
}

.header-fixed .header-limiter nav a:hover {
    opacity: 1;
}

.header-fixed .header-limiter nav a.selected {
    color: #608bd2;
    pointer-events: none;
    opacity: 1;
}

body.fixed .header-fixed {
    padding: 10px 40px;
    height: 50px;
    position: fixed;
    width: 100%;
    top: 0;
    left: 0;
    z-index: 1;
}

body.fixed .header-fixed .header-limiter h1 {
    font-size: 24px;
    line-height: 30px;
}

body.fixed .header-fixed .header-limiter nav {
    line-height: 28px;
    font-size: 13px;
}


@media all and (max-width: 600px) {
    .header-fixed {
        padding: 20px 0;
        height: 75px;
    }

    .header-fixed .header-limiter h1 {
        float: none;
        margin: -8px 0 10px;
        text-align: center;
        font-size: 24px;
        line-height: 1;
    }

    .header-fixed .header-limiter nav {
        line-height: 1;
        float: none;
    }

    .header-fixed .header-limiter nav a {
        font-size: 13px;
    }

    body.fixed .header-fixed {
        display: none;
    }
}

/* Styling the body */
* {
    margin: 0;
    padding: 0;
    font-family: 'Poppins', sans-serif;
    box-sizing: border-box;
}

body {
    margin: 0;
    padding: 0;
    background: url('images.jpeg');
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
}

/* header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
} */

.header-content {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: left;
}

header h1 {
    margin: 0;

}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

nav ul li {
    display: inline-block;
    margin-right: 20px;
}

nav ul li:last-child {
    margin-right: 0;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

nav ul li a:hover {
    text-decoration: underline;
}

/* header {
    background-color: #032552ee;
    color: white;
    padding: 20px;
    font-weight: bolder;
    align-items: center;
    display: flex;
} */

.mx-auto {
    display: flex;
    align-items: center;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
    position: fixed;
    left: 0;
    bottom: 0;
    width: 100%;


}

.footer-content {
    max-width: 1200px;
    margin: 0 auto;
}

section {
    width: 100%;
    height: 100vh;
    background:
        url();
    background-size: cover;
}

/* Styling the left floating section */
section .leftBox {
    width: 50%;
    height: 100%;
    float: left;
    padding: 50px;
    box-sizing: border-box;
}

/* Styling the background of 
			left floating section */
section .leftBox .content {
    color: #fff;
    background: rgba(0, 0, 0, 0.5);
    padding: 40px;
    transition: .5s;
}

/* Styling the hover effect 
			of left floating section */
section .leftBox .content:hover {
    background: #e91e63;
}

/* Styling the header of left 
			floating section */
section .leftBox .content h1 {
    margin: 0;
    padding: 0;
    font-size: 50px;
    text-transform: uppercase;
}

/* Styling the paragraph of 
			left floating section */
section .leftBox .content p {
    margin: 10px 0 0;
    padding: 0;
}

/* Styling the three events section */
section .events {
    position: relative;
    width: 50%;
    height: 100%;
    background: rgba(0, 0, 0, 0.5);
    float: right;
    box-sizing: border-box;
}

/* Styling the links of 
		the events section */
section .events ul {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    margin: 0;
    padding: 40px;
    box-sizing: border-box;
}

/* Styling the lists of the event section */
section .events ul li {
    list-style: none;
    background: #fff;
    box-sizing: border-box;
    height: 200px;
    margin: 15px 0;
}

/* Styling the time class of events section */
section .events ul li .time {
    position: relative;
    padding: 20px;
    background: #262626;
    box-sizing: border-box;
    width: 30%;
    height: 100%;
    float: left;
    text-align: center;
    transition: .5s;
}

/* Styling the hover effect
			of events section */
section .events ul li:hover .time {
    background: #e91e63;
}

/* Styling the header of time 
			class of events section */
section .events ul li .time h2 {
    position: absolute;
    margin: 0;
    padding: 0;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: #fff;
    font-size: 60px;
    line-height: 30px;
}

/* Styling the texts of time 
		class of events section */
section .events ul li .time h2 span {
    font-size: 30px;
}

/* Styling the details 
		class of events section */
section .events ul li .details {
    padding: 20px;
    background: #fff;
    box-sizing: border-box;
    width: 70%;
    height: 100%;
    float: left;
}

/* Styling the header of the 
		details class of events section */
section .events ul li .details h3 {
    position: relative;
    margin: 0;
    padding: 0;
    font-size: 22px;
}

/* Styling the lists of details 
		class of events section */
section .events ul li .details p {
    position: relative;
    margin: 10px 0 0;
    padding: 0;
    font-size: 16px;
}

/* Styling the links of details
		class of events section */
section .events ul li .details a {
    display: inline-block;
    text-decoration: none;
    padding: 10px 15px;
    border: 1.5px solid #262626;
    margin-top: 8px;
    font-size: 18px;
    transition: .5s;
}

/* Styling the details class's hover effect */
section .events ul li .details a:hover {
    background: #e91e63;
    color: #fff;
    border-color: #e91e63;
}

.center {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 50%;

}

a.home {
    color: #fff;
    text-align: left;
}

a.event {
    color: #fff;
}

a.about {
    color: #fff;
}

a.contact {
    color: #fff;
}

.top {
    text-align: center;
}

.header {
    background-color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 70px;
    margin-top: 10px;

}

/* Three image containers (use 25% for four, and 50% for two, etc) */
.column {
    float: left;
    width: 33.33%;
    padding: 5px;
}

/* Clear floats after image containers */
.row::after {
    content: "";
    clear: both;
    display: table;
    float: left;
}
.avatar {
    border-radius: 50%;
    width: 100px;
    height: 100px;
    overflow: hidden;
   
  }
