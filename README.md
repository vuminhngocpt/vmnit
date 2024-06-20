<html><!--<![endif]--><head>
		<meta charset="utf-8">
		<meta content="IE=edge,chrome=1" http-equiv="X-UA-Compatible">
		<title>SinhVienIT.Net Offline</title>	
		<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, user-scalable=no">
		<link rel="stylesheet" href="/offline/css/maximage.css" type="text/css" media="screen" charset="utf-8">
		<link rel="stylesheet" href="/offline/css/styles.css" type="text/css" media="screen" charset="utf-8">
		
		<!--[if lt IE 9]><script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script><![endif]-->
		
		<!--[if IE 6]>
			<style type="text/css" media="screen">
				.gradient {display:none;}
			</style>
		<![endif]-->
	</head>
	<body>

		<!-- Social Links -->
		<nav class="social-nav">
			<ul>
				<!-- li><a target="_blank" href="https://www.facebook.com/sinhvienit.fanpage/"><img src="images/icon-facebook.png" /></a></li -->
			</ul>
		</nav>

		<!-- Switch to full screen -->
		<button class="full-screen" onclick="$(document).toggleFullScreen()"></button>

		<!-- Site Logo -->
		<div id="logo" title="Thành lập từ ngày 11/11/2008">11/11/2008</div>

		<!-- Main Navigation -->
		<!-- nav class="main-nav">
			<ul>
				<li><a href="#home" class="active">Home</a></li>
				<li><a href="#about">About</a></li>
				<li><a href="#contact">Contact</a></li>
			</ul>
		</nav -->

		<!-- Home Page -->
		<section class="content show" id="home">
			<h1>Offline</h1>
			<h5>SinhVienIT.Net đã ngừng hoạt động!</h5>
			<p>Từ ngày 01/08/2019, website sinhvienit.net sẽ không còn hoạt động nữa. Đội ngũ phát triển sinhvienit.net rất cảm ơn các bạn đã đồng hành cùng chúng tôi trong suốt hơn 10 năm vừa qua. Hy vọng một ngày không xa, chúng ta có thể gặp nhau ở 1 phiên bản khác tốt hơn.</p>
			<p>Theo dõi sinhvienit.net tại Facebook <a target="_blank" rel="nofollow, noindex" href="https://www.facebook.com/sinhvienit.fanpage/"><b>SinhVienIT.Net Fanpage</b></a></p>
		</section>

		
		<!-- Background Slides -->
		<div id="maximage" class="mc-cycle" style="width: 414px; height: 616px; display: block;">
			
			
			
		<div class="mc-image " title="" style="background-image: url(&quot;/offline/images/backgrounds/bg-img-1.jpg&quot;); position: absolute; top: 0px; left: 0px; display: block; z-index: 3; opacity: 1; width: 414px; height: 616px;" data-href="">
				
				<img class="gradient" src="/offline/images/backgrounds/gradient.png" alt="" style="-webkit-user-select: none; -webkit-touch-callout: none;">
			</div><div class="mc-image " title="" style="background-image: url(&quot;/offline/images/backgrounds/bg-img-5.jpg&quot;); position: absolute; top: 0px; left: 0px; display: none; z-index: 2; width: 414px; height: 616px; opacity: 0;" data-href="">
				
				<img class="gradient" src="/offline/images/backgrounds/gradient.png" alt="" style="-webkit-user-select: none; -webkit-touch-callout: none;">
			</div></div>
		
		<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.8.3/jquery.js"></script>
		<script src="/offline/js/jquery.easing.min.js" type="text/javascript" charset="utf-8"></script>
		<script src="/offline/js/jquery.cycle.all.js" type="text/javascript" charset="utf-8"></script>
		<script src="/offline/js/jquery.maximage.js" type="text/javascript" charset="utf-8"></script>
		<script src="/offline/js/jquery.fullscreen.js" type="text/javascript" charset="utf-8"></script>
		<script src="/offline/js/jquery.ba-hashchange.js" type="text/javascript" charset="utf-8"></script>
		<script src="/offline/js/main.js" type="text/javascript" charset="utf-8"></script>
		
		<script type="text/javascript" charset="utf-8">
			$(function(){
				$('#maximage').maximage({
					cycleOptions: {
						fx: 'fade',
						speed: 1000, // Has to match the speed for CSS transitions in jQuery.maximage.css (lines 30 - 33)
						timeout: 5000,
						prev: '#arrow_left',
						next: '#arrow_right',
						pause: 0,
						before: function(last,current){
							if(!$.browser.msie){
								// Start HTML5 video when you arrive
								if($(current).find('video').length > 0) $(current).find('video')[0].play();
							}
						},
						after: function(last,current){
							if(!$.browser.msie){
								// Pauses HTML5 video when you leave it
								if($(last).find('video').length > 0) $(last).find('video')[0].pause();
							}
						}
					},
					onFirstImageLoaded: function(){
						jQuery('#cycle-loader').hide();
						jQuery('#maximage').fadeIn('fast');
					}
				});
	
				// Helper function to Fill and Center the HTML5 Video
				jQuery('video,object').maximage('maxcover');
	
			});
		</script>
  

</body></html>
