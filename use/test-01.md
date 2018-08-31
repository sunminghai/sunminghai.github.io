test01

```html
<!DOCTYPE html>
<html lang="zh-CN">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>微金所</title>
    <link rel="stylesheet" href="lib/css/bootstrap.min.css">
    <!--[if lt IE 9]>
      <script src="//cdn.bootcss.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="//cdn.bootcss.com/respond.js/1.4.2/respond.min.js"></script>
    <![endif]-->
    <link rel="stylesheet" href="css/base.css">
    <link rel="stylesheet" href="css/index.css">
</head>

<body>
    <!-- 顶部通栏 -->
    <div class="header hidden-md hidden-sm hidden-xs">
        <div class="container-fluid">
            <div class="row">
                <div class="col-lg-2">
                    <a class='wjs_font wjs_phone' href="#">手机微金所<span class="glyphicon glyphicon-chevron-down"></span></a>
                    <img src="images/code.jpg" alt="...">
                </div>
                <div class="col-lg-5">
                    <a class='glyphicon glyphicon-phone-alt' href="#">4006-89-4006（服务时间：9:00-21:00)</a>
                </div>
                <div class="col-lg-2">
                    <a href="#">常见问题</a>
                    <a href="#">财富登陆</a>
                </div>
                <div class="col-lg-3">
                    <input class="btn btn-danger btn-xs" type="button" value="免费注册">
                    <a href="#">登陆</a>
                </div>
            </div>
        </div>
    </div>
    <!-- 导航栏 -->
    <div class="nav">
        <nav class="navbar wjs-default">
            <div class="container-fluid">
                <!-- Brand and toggle get grouped for better mobile display -->
                <div class="navbar-header">
                    <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1"
                        aria-expanded="false">
                        <span class="sr-only">Toggle navigation</span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                    </button>
                    <a class="navbar-brand" href="#">
                        <span class="wjs_font wjs_logo"></span><span class="wjs_font wjs_word"></span>
                    </a>
                </div>

                <!-- Collect the nav links, forms, and other content for toggling -->
                <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
                    <ul class="nav navbar-nav">
                        <li class="active"><a href="#">我要投资</a></li>
                        <li><a href="#">我要接待</a></li>
                        <li><a href="#">投资介绍</a></li>
                        <li><a href="#">平台介绍</a></li>
                        <li><a href="#">内容介绍</a></li>
                        <li><a href="#">介绍介绍</a></li>
                    </ul>
                    <ul class="nav navbar-nav navbar-right hidden-sm hidden-xs">
                        <li><a href="#">个人中心</a></li>
                    </ul>
                </div><!-- /.navbar-collapse -->
            </div><!-- /.container-fluid -->
        </nav>
    </div>
    <div class="carousel">
        <div id="carousel-example-generic" class="carousel slide" data-ride="carousel">
            <!-- Indicators -->
            <ol class="carousel-indicators">
              <li data-target="#carousel-example-generic" data-slide-to="0" class="active"></li>
              <li data-target="#carousel-example-generic" data-slide-to="1"></li>
              <li data-target="#carousel-example-generic" data-slide-to="2"></li>
            </ol>
          
            <!-- Wrapper for slides -->
            <div class="carousel-inner" role="listbox">
              <div class="item active">
                <img src="..." alt="...">
                <div class="carousel-caption">
                  ...
                </div>
              </div>
              <div class="item">
                <img src="..." alt="...">
                <div class="carousel-caption">
                  ...
                </div>
              </div>
              ...
            </div>
          
            <!-- Controls -->
            <a class="left carousel-control" href="#carousel-example-generic" role="button" data-slide="prev">
              <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
              <span class="sr-only">Previous</span>
            </a>
            <a class="right carousel-control" href="#carousel-example-generic" role="button" data-slide="next">
              <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
              <span class="sr-only">Next</span>
            </a>
          </div>
    </div>

    <script src="lib/js/jquery.min.js"></script>
    <script src="lib/js/bootstrap.min.js"></script>
</body>

</html>
```