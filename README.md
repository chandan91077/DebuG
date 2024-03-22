# DebuG
<!DOCTYPE html>
<html lang="en">

<head>
	<link rel="stylesheet" href="HH.css">
</head>
<body>
    <header class="text-gray-600 body-font">
        <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
          <a class="flex title-font font-medium items-center text-gray-900 mb-4 md:mb-0">
            <img src="p22.webp" height="50" width="50">
            <span class="ml-3 text-xl">Product Launch Event Management</span>
          </a>
          <nav class="md:mr-auto md:ml-4 md:py-1 md:pl-4 md:border-l md:border-gray-400	flex flex-wrap items-center text-base justify-center">
            <a Href="Home.html" class="mr-5 hover:text-gray-900">Home</a>
            <a href="Event" class="mr-5 hover:text-gray-900">Event</a>
            <a href="about.html" class="mr-5 hover:text-gray-900">About</a>
            <a href="Contact us.html"class="mr-5 hover:text-gray-900">Contact us</a>
          </nav>
          
        </div>
      </header>
    

</body>
</html>

<body>
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
    <footer>
        <div class="footer-content">
            <p>&copy; 2024 Your Website. All rights reserved.</p>
        </div>
    </footer>  
</body>

</html>

<style>
		/* Styling the body */
        *{
            margin: 0;
            padding: 0;
            font-family: 'Poppins',sans-serif;
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
        header {
            background-color: #333; 
            color: #fff; 
            padding: 20px 0;
        }
        
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
 
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            font-weight: bolder;
            align-items: center;
            display: flex;
        
          }
          footer {
            background-color: #333;
            color: #fff; 
            padding: 20px 0; 
            text-align: center;
        }
        
        .footer-content {
            max-width: 1200px; 
            margin: 0 auto; 
        }
		section {
			width: 100%;
			height: 100vh;
			background:
				url(

				);
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
	</style>
