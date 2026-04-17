


<!DOCTYPE html>

<html>
<head><meta charset="UTF-8">
  <title>
	粵語網路課堂 Cantonese Online Tutorial
</title><link href="style/bootstrap-custom.min.css" rel="stylesheet" />
	<script src='/workshop/Chinese/Cantonese/OnlineTutorial/Scripts/bootstrap.js'></script>
	<script src='/workshop/Chinese/Cantonese/OnlineTutorial/Scripts/popper-utils.min.js'></script>

	<link href="style/style.min.css" rel="stylesheet" /><link href="style/css/font.css" rel="stylesheet" type="text/css" /><link href="style/css/foundation.css" rel="stylesheet" type="text/css" /><link href="style/css/jquery.fancybox.min.css" rel="stylesheet" type="text/css" /><link href="style/css/app.css" rel="stylesheet" type="text/css" /><link href="style/css/style.scss" rel="stylesheet" type="text/css" /><link rel="stylesheet" href="style/css/progres-bar.css" />


	<script>
        function ans() {
            alert("正確");
        }

        function ans2() {
            alert("再試一下");
        }
    </script>

	<script>
		function listBtn(caller) {
			var listBtn = caller;
			var textlistn = listBtn.nextElementSibling;

			/*
			var listBtn = document.getElementById('listBtn');
			var textlistn = document.getElementById('textlistn');
			*/

			if (textlistn.style.display === 'none') {
				textlistn.style.display = 'block';
				listBtn.innerText = "隱藏";
			} else {
				textlistn.style.display = 'none';
				listBtn.innerText = "按此看範例";
			}
		}
	</script>
</head>
<body>
    <form method="post" action="./courseListB.aspx" id="aspnetForm">
<div class="aspNetHidden">
<input type="hidden" name="__VIEWSTATE" id="__VIEWSTATE" value="59BMqP2y6FjnAiMi7uY9k/rYlJ5U1kuiHZA77iLxmCZzWsHU5TrMWAfbrlY+3Phr/aBL1PkBCKDRe/ZVV19ajJFrOGU=" />
</div>

<div class="aspNetHidden">

	<input type="hidden" name="__VIEWSTATEGENERATOR" id="__VIEWSTATEGENERATOR" value="6D9ADF00" />
</div>

		<div>
			<div class="pgJumbotron">
				<header data-sticky-container>
					<div class="top-bar sticky pgTopBar" data-sticky data-margin-top="0">
						<div class="top-bar-left">

						</div>

						<nav>
							<div class="top-bar-right" data-responsive-toggle="pgMenu" data-hide-for="medium">
								<button class="menu-icon" type="button" data-toggle="pgMenu"></button>
							</div>
							<div class="top-bar-right" id="pgMenu">
								<ul class="dropdown menu vertical medium-horizontal" data-dropdown-menu>
									<li><a href="index.aspx">主頁</a></li>
									<li><a href="romanization.aspx">語音知識</a></li>
									<li class="is-dropdown-submenu-parent">
										<a href="javascript:void(0);">粵語課程</a>
										<ul class="menu vertical">
											<li><a href="courseListA.aspx#pgContent">初級</a></li>
											<li><a href="courseListB.aspx#pgContent">中級</a></li>
										</ul>
									</li>
									<li><a href="about.aspx">關於我們</a></li>
								</ul>
							</div>
						</nav>
					</div>
				</header>
				<div class="grid-container grid-container-padded">
					<div class="grid-x align-center-middle">
						<div class="cell text-center">
							<div id="pageTitle">

								<div class="title align-bottom text-left"">
									<h1 class="align-bottom text-left">
									
									
									</h1>
								</div>
							</div>

							<div class="container">
							<h1>粵語網路課堂</h1>
							<p class="motto">
								粵語是漢語方言之一，通行於廣東省大部分地區。據專家統計，包括海外華人在內，用粵語溝通的人不少於七千萬人。粵語作為漢語方言，與普通話固然有著許多相同的地方。然而兩者在語音、辭彙和語法各方面都有不少差異。我們應當注意粵語與普通話的對應關係，找出其中的規律以便提高學習效率。
							</p>
						</div>
						<div class="cell">

						</div>
					</div>
				</div>
			</div>

			<section id="pgContent">
				
				
			</section>

		</div>

			<div>
				

	<div class="pgContainer grid-container">
		<div class="grid-x align-center grid-padding-x grid-padding-y padding">
			<div class="cell text-center">
					<h2>粵語課程</h2>
                        <p>
                            本章節分初級及中級的常用粵語內容。
                        </p>
			</div>
		</div>
	</div>

	<div id="Llink" class="pgContainer shaded" id="#1">
		<div class="grid-container grid-x">
			<div class="pgContainer" id="#2">
				<div class="grid-container grid-x">
					<div class="cell">
						<h2 class="text-center">中級</h2>
					</div>

					<div class="grid-x align-center grid-padding-x grid-padding-y padding">
						<a class="cell small-12 medium-4 text-center" href="courseList_c1.aspx">
							<div class="icon"><img src="img/LessonB_01.png" alt="粵語課程中級第一課中大校園生活" title="粵語課程中級中大校園生活" width="200" /></div>
							<div class="h4">中大校園生活</div>
						</a>
						<a class="cell small-12 medium-4 text-center" href="courseList_c2.aspx">
							<div class="icon"><img src="img/LessonB_02.png" alt="粵語課程中級第二課人際關係" title="粵語課程中級人際關係" width="200" /></div>
							<div class="h4">人際關係</div>
						</a>
						<a class="cell small-12 medium-4 text-center" href="courseList_c3.aspx">
							<div class="icon"><img src="img/LessonB_03.png" alt="粵語課程中級第三課興趣愛好" title="粵語課程中級興趣愛好" width="200" /></div>
							<div class="h4">興趣愛好</div>
						</a>
						<a class="cell small-12 medium-4 text-center" href="courseList_c4.aspx">
							<div class="icon"><img src="img/LessonB_04.png" alt="粵語課程中級第四課生活風情" title="粵語課程中級生活風情" width="200" /></div>
							<div class="h4">生活風情</div>
						</a>
						<a class="cell small-12 medium-4 text-center" href="courseList_c5.aspx">
							<div class="icon"><img src="img/LessonB_05.png" alt="粵語課程中級第五課新聞書刊" title="粵語課程中級新聞書刊" width="200" /></div>
							<div class="h4">新聞書刊</div>
						</a>
					</div>
				</div>
			</div>
		</div>
	</div>

	<div id="Llink2" class="pgContainer grid-container">
		<div class="grid-x align-center grid-padding-x grid-padding-y padding">
			<div class="cell text-center">
					<h2>初級課程</h2>
				<a class="cell small-12 medium-4 text-center" href="courseListA.aspx">
					<div class="h4">前往</div>
				</a>
			</div>
		</div>
	</div>

			</div>

			<div>
				
				
			</div>

		<!-- footer -->
		<footer>
			<div class="pgFooter">
				<div class="grid-container">
					<div class="grid-x grid-padding-x grid-padding-y">
						<div class="cell small-12 medium-4 large-3">
							<strong>香港中文大學自學中心</strong>
							<div>
							(852) 3943 8733<br />
							<a href="mailto:ilc-counsel@cuhk.edu.hk">ilc-counsel@cuhk.edu.hk</a><br />
							聯合書院胡忠圖書館1樓
							</div>
							<strong>Copyright</strong>
							<div>版權所有 &copy; 2026. 香港中文大學自學中心</div>
						</div>

					</div>
				</div>
			</div>
		</footer>
        </div>
    </form>

	<script src="js/vendor/jquery.js" type="text/javascript"></script>
	<script src="js/vendor/foundation.min.js" type="text/javascript"></script>
	<script src="js/vendor/what-input.js" type="text/javascript"></script>
	<script src="js/jquery.fancybox.min.js" type="text/javascript"></script>
	<script src="js/app.js"></script>

	<script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
	<script src="js/player.js"></script>

	<script>
        $(document).ready(function () {
            $('.mediPlayer').mediaPlayer();
        });
    </script>

	<script type="text/javascript">

        var _gaq = _gaq || [];
        _gaq.push(['_setAccount', 'UA-36251023-1']);
        _gaq.push(['_setDomainName', 'jqueryscript.net']);
        _gaq.push(['_trackPageview']);

        (function () {
            var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
            ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
            var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
        })();

    </script>
</body>
</html>
