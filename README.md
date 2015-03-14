# JS-CodeStyle
<html lang="en" class=""><head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    
    
    <title>javascript/README.md at master · airbnb/javascript</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site"><meta content="summary" name="twitter:card"><meta content="airbnb/javascript" name="twitter:title"><meta content="javascript - JavaScript Style Guide" name="twitter:description"><meta content="https://avatars2.githubusercontent.com/u/698437?v=3&amp;s=400" name="twitter:image:src">
      <meta content="GitHub" property="og:site_name"><meta content="object" property="og:type"><meta content="https://avatars2.githubusercontent.com/u/698437?v=3&amp;s=400" property="og:image"><meta content="airbnb/javascript" property="og:title"><meta content="https://github.com/airbnb/javascript" property="og:url"><meta content="javascript - JavaScript Style Guide" property="og:description">
      <meta name="browser-stats-url" content="/_stats">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="conduit-xhr" href="https://ghconduit.com:25035">
    <link rel="xhr-socket" href="/_sockets">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    
      <meta name="google-analytics" content="UA-3769691-2">

    <meta content="collector.githubapp.com" name="octolytics-host"><meta content="collector-cdn.github.com" name="octolytics-script-host"><meta content="github" name="octolytics-app-id"><meta content="86F9A435:51F6:388DE6B:5503D32C" name="octolytics-dimension-request_id"><meta content="1990628" name="octolytics-actor-id"><meta content="YourTradingSystems" name="octolytics-actor-login"><meta content="ae14e69134f64551c7b001a6e8980755319918929f7122ed21d22aaf9084a0b8" name="octolytics-actor-hash">
    
    <meta content="Rails, view, files#disambiguate" name="analytics-event">

    
    <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">


    <meta content="authenticity_token" name="csrf-param">
<meta content="U6cILCJ82m3CTCHf96CcMYy1jIWoE+P29ZKSMYZgSWv/IRN3LpuCn3wdyfqmyyAA4aQAWfCVueuUdwU1TlL1jg==" name="csrf-token">

    <link href="https://assets-cdn.github.com/assets/github-85e4ac99403eefa73664d9b122f27095fee8b7333e67f34fa34480ae497f7555.css" media="all" rel="stylesheet">
    <link href="https://assets-cdn.github.com/assets/github2-901780fdaaa6b0f56b2004899a7a24194bf4217cc7864291a9f68fa3a9264fdf.css" media="all" rel="stylesheet">
    
    


    <meta http-equiv="x-pjax-version" content="8060cc7a9543870628764b4fdb4264ea">

      
  <meta name="description" content="javascript - JavaScript Style Guide">
  <meta name="go-import" content="github.com/airbnb/javascript git https://github.com/airbnb/javascript.git">

  <meta content="698437" name="octolytics-dimension-user_id"><meta content="airbnb" name="octolytics-dimension-user_login"><meta content="6498492" name="octolytics-dimension-repository_id"><meta content="airbnb/javascript" name="octolytics-dimension-repository_nwo"><meta content="true" name="octolytics-dimension-repository_public"><meta content="false" name="octolytics-dimension-repository_is_fork"><meta content="6498492" name="octolytics-dimension-repository_network_root_id"><meta content="airbnb/javascript" name="octolytics-dimension-repository_network_root_nwo">
  <link href="https://github.com/airbnb/javascript/commits/master.atom" rel="alternate" title="Recent Commits to javascript:master" type="application/atom+xml">

  <style type="text/css"></style><script type="text/javascript" async="" src="//collector-cdn.github.com/assets/api.js"></script><meta name="selected-link" value="repo_source" data-pjax-transient="true"><meta content="Rails, view, blob#show" name="analytics-event" data-pjax-transient="true"></head>


  <body class="logged_in  env-production windows vis-public">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>
    <div class="wrapper">
      
      
      


        <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <span class="mega-octicon octicon-mark-github"></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <form accept-charset="UTF-8" action="/airbnb/javascript/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/airbnb/javascript/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="✓"></div>
  <input type="text" class="js-site-search-field is-clearable" data-hotkey="s" name="q" placeholder="Search" data-global-scope-placeholder="Search GitHub" data-repo-scope-placeholder="Search" tabindex="1" autocapitalize="off">
  <div class="scope-badge">This repository</div>
</form>
      </div>
      <ul class="header-nav left" role="navigation">
        <li class="header-nav-item explore">
          <a class="header-nav-link" href="/explore" data-ga-click="Header, go to explore, text:explore">Explore</a>
        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="/blog" data-ga-click="Header, go to blog, text:blog">Blog</a>
          </li>
        <li class="header-nav-item">
          <a class="header-nav-link" href="https://help.github.com" data-ga-click="Header, go to help, text:help">Help</a>
        </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name" href="/YourTradingSystems" data-ga-click="Header, go to profile, text:username">
      <img alt="Alexander" class="avatar" data-user="1990628" height="20" src="https://avatars0.githubusercontent.com/u/1990628?v=3&amp;s=40" width="20">
      <span class="css-truncate">
        <span class="css-truncate-target">YourTradingSystems</span>
      </span>
    </a>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link js-menu-target tooltipped tooltipped-s" href="#" aria-label="Create new..." data-ga-click="Header, create new, icon:add">
      <span class="octicon octicon-plus"></span>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      
<ul class="dropdown-menu">
  <li>
    <a href="/new" data-ga-click="Header, create new repository, icon:repo"><span class="octicon octicon-repo"></span> New repository</a>
  </li>
  <li>
    <a href="/organizations/new" data-ga-click="Header, create new organization, icon:organization"><span class="octicon octicon-organization"></span> New organization</a>
  </li>


    <li class="dropdown-divider"></li>
    <li class="dropdown-header">
      <span title="airbnb/javascript">This repository</span>
    </li>
      <li>
        <a href="/airbnb/javascript/issues/new" data-ga-click="Header, create new issue, icon:issue"><span class="octicon octicon-issue-opened"></span> New issue</a>
      </li>
</ul>

    </div>
  </li>

  <li class="header-nav-item">
        <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
        <span class="mail-status all-read"></span>
        <span class="octicon octicon-inbox"></span>
</a>
  </li>

  <li class="header-nav-item">
    <a class="header-nav-link tooltipped tooltipped-s" href="/settings/profile" id="account_settings" aria-label="Settings" data-ga-click="Header, go to settings, icon:settings">
      <span class="octicon octicon-gear"></span>
    </a>
  </li>

  <li class="header-nav-item">
    <form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="✓"><input name="authenticity_token" type="hidden" value="DsdaqLpzXgUoz25F1OeTBO1bNLmCXSoYAP5L4c8eLviKm0mj7Tt0KYkyhcXB3S/V7W/lcbYdHpFDUm+dhFVsoQ=="></div>
      <button class="header-nav-link sign-out-button tooltipped tooltipped-s" aria-label="Sign out" data-ga-click="Header, sign out, icon:logout">
        <span class="octicon octicon-sign-out"></span>
      </button>
</form>  </li>

</ul>


    
  </div>
</div>

        

        


      <div id="start-of-content" class="accessibility-aid"></div>
          <div class="site" itemscope="" itemtype="http://schema.org/WebPage">
    <div id="js-flash-container"><div id="pjax-flash">
  
</div></div>
    <div class="pagehead repohead instapaper_ignore readability-menu">
      <div class="container">
        
<ul class="pagehead-actions">

  <li>
      <form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="✓"><input name="authenticity_token" type="hidden" value="IHDF8P63w99mAvY88j8aY/u5w/sYQAVaBPWG7pZeHI8siQGEVrbtzyEO0MYIId+VC0gKTaxxZxTOeOC3xDx0nQ=="></div>    <input id="repository_id" name="repository_id" type="hidden" value="6498492">

      <div class="select-menu js-menu-container js-select-menu">
        <a href="/airbnb/javascript/subscription" class="minibutton select-menu-button with-count js-menu-target" role="button" tabindex="0" aria-haspopup="true" data-ga-click="Repository, click Watch settings, action:files#disambiguate">
          <span class="js-select-button">
            <span class="octicon octicon-eye"></span>
            Watch
          </span>
        </a>
        <a class="social-count js-social-count" href="/airbnb/javascript/watchers">
          1,001
        </a>
        
        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header">
              <span class="select-menu-title">Notifications</span>
              <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
            </div>

            <div class="select-menu-list js-navigation-container" role="menu">

              <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input checked="checked" id="do_included" name="do" type="radio" value="included">
                  <span class="select-menu-item-heading">Not watching</span>
                  <span class="description">Be notified when participating or @mentioned.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Watch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_subscribed" name="do" type="radio" value="subscribed">
                  <span class="select-menu-item-heading">Watching</span>
                  <span class="description">Be notified of all conversations.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Unwatch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_ignore" name="do" type="radio" value="ignore">
                  <span class="select-menu-item-heading">Ignoring</span>
                  <span class="description">Never be notified.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-mute"></span>
                    Stop ignoring
                  </span>
                </div>
              </div>

            </div>

          </div>
        </div>
      </div>
</form>
  </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">

    <form accept-charset="UTF-8" action="/airbnb/javascript/unstar" class="js-toggler-form starred js-unstar-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="✓"><input name="authenticity_token" type="hidden" value="1XOKTJWlz0JWkAfC+CFOjGDb7TPYG880rLmit9/JK2Qijp9nlit7tcQt3qyX93OpdX6lMt3hKfGiCeEEqtXOWA=="></div>
      <button class="minibutton with-count js-toggler-target" aria-label="Unstar this repository" title="Unstar airbnb/javascript" data-ga-click="Repository, click unstar button, action:files#disambiguate; text:Unstar">
        <span class="octicon octicon-star"></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/airbnb/javascript/stargazers">
          12,846
        </a>
</form>
    <form accept-charset="UTF-8" action="/airbnb/javascript/star" class="js-toggler-form unstarred js-star-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="✓"><input name="authenticity_token" type="hidden" value="8kszA31u0nJUGoAb80jG6aS08KIN0/vcrfkISBt7KX196IWGire3rvDPYWplvl0AcIjHe9c9w1eDf30bITUOsw=="></div>
      <button class="minibutton with-count js-toggler-target" aria-label="Star this repository" title="Star airbnb/javascript" data-ga-click="Repository, click star button, action:files#disambiguate; text:Star">
        <span class="octicon octicon-star"></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/airbnb/javascript/stargazers">
          12,846
        </a>
</form>  </div>

  </li>

        <li>
          <form accept-charset="UTF-8" action="/airbnb/javascript/fork" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="✓"><input name="authenticity_token" type="hidden" value="Y79/QyLMvj81ChjwdNkxN/vcJyPYPks+VaYssNdxiLs/wAnbxO0SzJIg2XA8z+U3Y8Y0J92/r5nrCp6qwocayg=="></div>
            <button type="submit" class="minibutton with-count" data-ga-click="Repository, show fork modal, action:files#disambiguate; text:Fork" title="Fork your own copy of airbnb/javascript to your account" aria-label="Fork your own copy of airbnb/javascript to your account">
              <span class="octicon octicon-repo-forked"></span>
              Fork
            </button>
            <a href="/airbnb/javascript/network" class="social-count">2,612</a>
</form>        </li>

</ul>

        <h1 itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
          <span class="mega-octicon octicon-repo"></span>
          <span class="author"><a href="/airbnb" class="url fn" itemprop="url" rel="author"><span itemprop="title">airbnb</span></a></span><!--
       --><span class="path-divider">/</span><!--
       --><strong><a href="/airbnb/javascript" class="js-current-repository" data-pjax="#js-repo-pjax-container">javascript</a></strong>

          <span class="page-context-loader">
            <img alt="" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16">
          </span>

        </h1>
      </div><!-- /.container -->
    </div><!-- /.repohead -->

    <div class="container">
      <div class="repository-with-sidebar repo-container new-discussion-timeline">
        <div class="repository-sidebar clearfix">
            
<nav class="sunken-menu repo-nav js-repo-nav js-sidenav-container-pjax js-octicon-loaders" role="navigation" data-pjax="#js-repo-pjax-container" data-issue-count-url="/airbnb/javascript/issues/counts">
  <ul class="sunken-menu-group">
    <li class="tooltipped tooltipped-w" aria-label="Code">
      <a href="/airbnb/javascript" aria-label="Code" class="js-selected-navigation-item sunken-menu-item selected" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /airbnb/javascript">
        <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16">
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Issues">
        <a href="/airbnb/javascript/issues" aria-label="Issues" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /airbnb/javascript/issues">
          <span class="octicon octicon-issue-opened"></span> <span class="full-word">Issues</span>
          <span class="counter">17</span>

          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16">
</a>      </li>

    <li class="tooltipped tooltipped-w" aria-label="Pull Requests">
      <a href="/airbnb/javascript/pulls" aria-label="Pull Requests" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g p" data-selected-links="repo_pulls /airbnb/javascript/pulls">
          <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull Requests</span>
          <span class="counter">15</span>

          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16">
</a>    </li>


      <li class="tooltipped tooltipped-w" aria-label="Wiki">
        <a href="/airbnb/javascript/wiki" aria-label="Wiki" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g w" data-selected-links="repo_wiki /airbnb/javascript/wiki">
          <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16">
</a>      </li>
  </ul>
  <div class="sunken-menu-separator"></div>
  <ul class="sunken-menu-group">

    <li class="tooltipped tooltipped-w" aria-label="Pulse">
      <a href="/airbnb/javascript/pulse" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-selected-links="pulse /airbnb/javascript/pulse">
        <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16">
</a>    </li>

    <li class="tooltipped tooltipped-w" aria-label="Graphs">
      <a href="/airbnb/javascript/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_graphs repo_contributors /airbnb/javascript/graphs">
        <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16">
</a>    </li>
  </ul>


</nav>

              <div class="only-with-full-nav">
                  
<div class="clone-url open" data-protocol-type="http" data-url="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone">
  <h3><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target" value="https://github.com/airbnb/javascript.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url " data-protocol-type="ssh" data-url="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=clone">
  <h3><span class="text-emphasized">SSH</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target" value="git@github.com:airbnb/javascript.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url " data-protocol-type="subversion" data-url="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=clone">
  <h3><span class="text-emphasized">Subversion</span> checkout URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target" value="https://github.com/airbnb/javascript" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>



<p class="clone-options">You can clone with
  <a href="#" class="js-clone-selector" data-protocol="http">HTTPS</a>, <a href="#" class="js-clone-selector" data-protocol="ssh">SSH</a>, or <a href="#" class="js-clone-selector" data-protocol="subversion">Subversion</a>.
  <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <span class="octicon octicon-question"></span>
  </a>
</p>


  <a href="github-windows://openRepo/https://github.com/airbnb/javascript" class="minibutton sidebar-button" title="Save airbnb/javascript to your computer and use it in GitHub Desktop." aria-label="Save airbnb/javascript to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-device-desktop"></span>
    Clone in Desktop
  </a>

                <a href="/airbnb/javascript/archive/master.zip" class="minibutton sidebar-button" aria-label="Download the contents of airbnb/javascript as a zip file" title="Download the contents of airbnb/javascript as a zip file" rel="nofollow">
                  <span class="octicon octicon-cloud-download"></span>
                  Download ZIP
                </a>
              </div>
        </div><!-- /.repository-sidebar -->

        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container="">  

<a href="/airbnb/javascript/blob/b3e83dcaa57d6679d0e972dcf163d81a51779b1d/README.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:051eafe6a722f1d002b0ac54f445d40f -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu js-menu-container js-select-menu left">
  <span class="minibutton select-menu-button js-menu-target css-truncate" data-hotkey="w" data-master-branch="master" data-ref="master" title="master" role="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <span class="octicon octicon-git-branch"></span>
    <i>branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </span>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax="" aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span class="select-menu-title">Switch branches/tags</span>
        <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open " href="/airbnb/javascript/blob/attribution_for_all/README.md" data-name="attribution_for_all" data-skip-pjax="true" rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="attribution_for_all">
                attribution_for_all
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open " href="/airbnb/javascript/blob/gh-pages/README.md" data-name="gh-pages" data-skip-pjax="true" rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="gh-pages">
                gh-pages
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open " href="/airbnb/javascript/blob/jslint-vim/README.md" data-name="jslint-vim" data-skip-pjax="true" rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="jslint-vim">
                jslint-vim
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open selected" href="/airbnb/javascript/blob/master/README.md" data-name="master" data-skip-pjax="true" rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="master">
                master
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

  <div class="button-group right">
    <a href="/airbnb/javascript/find/master" class="js-show-file-finder minibutton empty-icon tooltipped tooltipped-s" data-pjax="" data-hotkey="t" aria-label="Quickly jump between files">
      <span class="octicon octicon-list-unordered"></span>
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
  </div>

  <div class="breadcrumb js-zeroclipboard-target">
    <span class="repo-root js-repo-root"><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/airbnb/javascript" class="" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">javascript</span></a></span></span><span class="separator">/</span><strong class="final-path">README.md</strong>
  </div>
</div>


  <div class="commit file-history-tease">
    <div class="file-history-tease-header">
        <img alt="Jake Teton-Landis" class="avatar" data-user="296279" height="24" src="https://avatars0.githubusercontent.com/u/296279?v=3&amp;s=48" width="24">
        <span class="author"><a href="/justjake" rel="contributor">justjake</a></span>
        <time datetime="2015-03-11T22:01:14Z" is="relative-time" title="12 бер. 2015 00:01 GMT+2">2 days ago</time>
        <div class="commit-title">
            <a href="/airbnb/javascript/commit/e9b573287c405d67b9a92f213df137f11a011913" class="message" data-pjax="true" title="naming files containing one class">naming files containing one class</a>
        </div>
    </div>

    <div class="participation">
      <p class="quickstat">
        <a href="#blob_contributors_box" rel="facebox">
          <strong>78</strong>
           contributors
        </a>
      </p>
          <a class="avatar-link tooltipped tooltipped-s" aria-label="hshoff" href="/airbnb/javascript/commits/master/README.md?author=hshoff"><img alt="Harrison Shoff" class="avatar" data-user="339208" height="20" src="https://avatars1.githubusercontent.com/u/339208?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="thisconnect" href="/airbnb/javascript/commits/master/README.md?author=thisconnect"><img alt="tcme" class="avatar" data-user="546900" height="20" src="https://avatars0.githubusercontent.com/u/546900?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="justjake" href="/airbnb/javascript/commits/master/README.md?author=justjake"><img alt="Jake Teton-Landis" class="avatar" data-user="296279" height="20" src="https://avatars2.githubusercontent.com/u/296279?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="mitsuruog" href="/airbnb/javascript/commits/master/README.md?author=mitsuruog"><img alt="Mitsuru Ogawa" class="avatar" data-user="1703219" height="20" src="https://avatars3.githubusercontent.com/u/1703219?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="mjurczyk" href="/airbnb/javascript/commits/master/README.md?author=mjurczyk"><img alt="MJurczyk" class="avatar" data-user="9549760" height="20" src="https://avatars1.githubusercontent.com/u/9549760?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="spikebrehm" href="/airbnb/javascript/commits/master/README.md?author=spikebrehm"><img alt="Spike Brehm" class="avatar" data-user="133937" height="20" src="https://avatars0.githubusercontent.com/u/133937?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="nmussy" href="/airbnb/javascript/commits/master/README.md?author=nmussy"><img alt="Jimmy Gaussen" class="avatar" data-user="2505696" height="20" src="https://avatars2.githubusercontent.com/u/2505696?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="timofurrer" href="/airbnb/javascript/commits/master/README.md?author=timofurrer"><img alt="Timo Furrer" class="avatar" data-user="1008252" height="20" src="https://avatars3.githubusercontent.com/u/1008252?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="unkillbob" href="/airbnb/javascript/commits/master/README.md?author=unkillbob"><img alt="James Bunt" class="avatar" data-user="1883524" height="20" src="https://avatars2.githubusercontent.com/u/1883524?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="koenpunt" href="/airbnb/javascript/commits/master/README.md?author=koenpunt"><img alt="Koen Punt" class="avatar" data-user="351038" height="20" src="https://avatars0.githubusercontent.com/u/351038?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="joaomilho" href="/airbnb/javascript/commits/master/README.md?author=joaomilho"><img alt="Juan Lulkin" class="avatar" data-user="308196" height="20" src="https://avatars1.githubusercontent.com/u/308196?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="reissbaker" href="/airbnb/javascript/commits/master/README.md?author=reissbaker"><img alt="Matt Baker" class="avatar" data-user="803092" height="20" src="https://avatars1.githubusercontent.com/u/803092?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="TheSavior" href="/airbnb/javascript/commits/master/README.md?author=TheSavior"><img alt="Eli White" class="avatar" data-user="249164" height="20" src="https://avatars0.githubusercontent.com/u/249164?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="goldcaddy77" href="/airbnb/javascript/commits/master/README.md?author=goldcaddy77"><img alt="Dan Caddigan" class="avatar" data-user="573625" height="20" src="https://avatars0.githubusercontent.com/u/573625?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="nicoder" href="/airbnb/javascript/commits/master/README.md?author=nicoder"><img alt="Nicolas Dermine" class="avatar" data-user="365210" height="20" src="https://avatars3.githubusercontent.com/u/365210?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="iamnirav" href="/airbnb/javascript/commits/master/README.md?author=iamnirav"><img alt="Nirav Sanghani" class="avatar" data-user="313886" height="20" src="https://avatars1.githubusercontent.com/u/313886?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="ClimbsRocks" href="/airbnb/javascript/commits/master/README.md?author=ClimbsRocks"><img alt="Preston Parry" class="avatar" data-user="7017045" height="20" src="https://avatars2.githubusercontent.com/u/7017045?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="godspeedelbow" href="/airbnb/javascript/commits/master/README.md?author=godspeedelbow"><img alt="Eelke Boezeman" class="avatar" data-user="1466424" height="20" src="https://avatars2.githubusercontent.com/u/1466424?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="paolocarrasco" href="/airbnb/javascript/commits/master/README.md?author=paolocarrasco"><img alt="Paolo Carrasco" class="avatar" data-user="1524522" height="20" src="https://avatars2.githubusercontent.com/u/1524522?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="pborreli" href="/airbnb/javascript/commits/master/README.md?author=pborreli"><img alt="Pascal Borreli" class="avatar" data-user="77759" height="20" src="https://avatars1.githubusercontent.com/u/77759?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="tipjs" href="/airbnb/javascript/commits/master/README.md?author=tipjs"><img alt="SeungHyun PAEK" class="avatar" data-user="2290655" height="20" src="https://avatars3.githubusercontent.com/u/2290655?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="pyrotechnick" href="/airbnb/javascript/commits/master/README.md?author=pyrotechnick"><img alt="Nicholas Kinsey" class="avatar" data-user="13998" height="20" src="https://avatars2.githubusercontent.com/u/13998?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="Joe8Bit" href="/airbnb/javascript/commits/master/README.md?author=Joe8Bit"><img alt="Joe Pettersson" class="avatar" data-user="467683" height="20" src="https://avatars3.githubusercontent.com/u/467683?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="doshprompt" href="/airbnb/javascript/commits/master/README.md?author=doshprompt"><img alt="Rahul Doshi" class="avatar" data-user="1147078" height="20" src="https://avatars2.githubusercontent.com/u/1147078?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="qorbani" href="/airbnb/javascript/commits/master/README.md?author=qorbani"><img alt="Reza Qorbani" class="avatar" data-user="771382" height="20" src="https://avatars3.githubusercontent.com/u/771382?v=3&amp;s=40" width="20"></a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="lxe" href="/airbnb/javascript/commits/master/README.md?author=lxe"><img alt="Aleksey Smolenchuk" class="avatar" data-user="1486609" height="20" src="https://avatars0.githubusercontent.com/u/1486609?v=3&amp;s=40" width="20"></a>

    <a href="#blob_contributors_box" rel="facebox" class="others-text">and others</a>

    </div>
    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list">
          <li class="facebox-user-list-item">
            <img alt="Harrison Shoff" data-user="339208" height="24" src="https://avatars3.githubusercontent.com/u/339208?v=3&amp;s=48" width="24">
            <a href="/hshoff">hshoff</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="tcme" data-user="546900" height="24" src="https://avatars2.githubusercontent.com/u/546900?v=3&amp;s=48" width="24">
            <a href="/thisconnect">thisconnect</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Jake Teton-Landis" data-user="296279" height="24" src="https://avatars0.githubusercontent.com/u/296279?v=3&amp;s=48" width="24">
            <a href="/justjake">justjake</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Mitsuru Ogawa" data-user="1703219" height="24" src="https://avatars1.githubusercontent.com/u/1703219?v=3&amp;s=48" width="24">
            <a href="/mitsuruog">mitsuruog</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="MJurczyk" data-user="9549760" height="24" src="https://avatars3.githubusercontent.com/u/9549760?v=3&amp;s=48" width="24">
            <a href="/mjurczyk">mjurczyk</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Spike Brehm" data-user="133937" height="24" src="https://avatars2.githubusercontent.com/u/133937?v=3&amp;s=48" width="24">
            <a href="/spikebrehm">spikebrehm</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Jimmy Gaussen" data-user="2505696" height="24" src="https://avatars0.githubusercontent.com/u/2505696?v=3&amp;s=48" width="24">
            <a href="/nmussy">nmussy</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Timo Furrer" data-user="1008252" height="24" src="https://avatars1.githubusercontent.com/u/1008252?v=3&amp;s=48" width="24">
            <a href="/timofurrer">timofurrer</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="James Bunt" data-user="1883524" height="24" src="https://avatars0.githubusercontent.com/u/1883524?v=3&amp;s=48" width="24">
            <a href="/unkillbob">unkillbob</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Koen Punt" data-user="351038" height="24" src="https://avatars2.githubusercontent.com/u/351038?v=3&amp;s=48" width="24">
            <a href="/koenpunt">koenpunt</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Juan Lulkin" data-user="308196" height="24" src="https://avatars3.githubusercontent.com/u/308196?v=3&amp;s=48" width="24">
            <a href="/joaomilho">joaomilho</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Matt Baker" data-user="803092" height="24" src="https://avatars3.githubusercontent.com/u/803092?v=3&amp;s=48" width="24">
            <a href="/reissbaker">reissbaker</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Eli White" data-user="249164" height="24" src="https://avatars2.githubusercontent.com/u/249164?v=3&amp;s=48" width="24">
            <a href="/TheSavior">TheSavior</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Dan Caddigan" data-user="573625" height="24" src="https://avatars2.githubusercontent.com/u/573625?v=3&amp;s=48" width="24">
            <a href="/goldcaddy77">goldcaddy77</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Nicolas Dermine" data-user="365210" height="24" src="https://avatars1.githubusercontent.com/u/365210?v=3&amp;s=48" width="24">
            <a href="/nicoder">nicoder</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Nirav Sanghani" data-user="313886" height="24" src="https://avatars3.githubusercontent.com/u/313886?v=3&amp;s=48" width="24">
            <a href="/iamnirav">iamnirav</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Preston Parry" data-user="7017045" height="24" src="https://avatars0.githubusercontent.com/u/7017045?v=3&amp;s=48" width="24">
            <a href="/ClimbsRocks">ClimbsRocks</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Eelke Boezeman" data-user="1466424" height="24" src="https://avatars0.githubusercontent.com/u/1466424?v=3&amp;s=48" width="24">
            <a href="/godspeedelbow">godspeedelbow</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Paolo Carrasco" data-user="1524522" height="24" src="https://avatars0.githubusercontent.com/u/1524522?v=3&amp;s=48" width="24">
            <a href="/paolocarrasco">paolocarrasco</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Pascal Borreli" data-user="77759" height="24" src="https://avatars3.githubusercontent.com/u/77759?v=3&amp;s=48" width="24">
            <a href="/pborreli">pborreli</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="SeungHyun PAEK" data-user="2290655" height="24" src="https://avatars1.githubusercontent.com/u/2290655?v=3&amp;s=48" width="24">
            <a href="/tipjs">tipjs</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Nicholas Kinsey" data-user="13998" height="24" src="https://avatars0.githubusercontent.com/u/13998?v=3&amp;s=48" width="24">
            <a href="/pyrotechnick">pyrotechnick</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Joe Pettersson" data-user="467683" height="24" src="https://avatars1.githubusercontent.com/u/467683?v=3&amp;s=48" width="24">
            <a href="/Joe8Bit">Joe8Bit</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Rahul Doshi" data-user="1147078" height="24" src="https://avatars0.githubusercontent.com/u/1147078?v=3&amp;s=48" width="24">
            <a href="/doshprompt">doshprompt</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Reza Qorbani" data-user="771382" height="24" src="https://avatars1.githubusercontent.com/u/771382?v=3&amp;s=48" width="24">
            <a href="/qorbani">qorbani</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Aleksey Smolenchuk" data-user="1486609" height="24" src="https://avatars2.githubusercontent.com/u/1486609?v=3&amp;s=48" width="24">
            <a href="/lxe">lxe</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Adam" data-user="92850" height="24" src="https://avatars3.githubusercontent.com/u/92850?v=3&amp;s=48" width="24">
            <a href="/adamlu">adamlu</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Leonardo Micheloni" data-user="1152021" height="24" src="https://avatars1.githubusercontent.com/u/1152021?v=3&amp;s=48" width="24">
            <a href="/leomicheloni">leomicheloni</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Kiryl Yermakou" data-user="470292" height="24" src="https://avatars2.githubusercontent.com/u/470292?v=3&amp;s=48" width="24">
            <a href="/rma4ok">rma4ok</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Stefan Thomas" data-user="53233" height="24" src="https://avatars2.githubusercontent.com/u/53233?v=3&amp;s=48" width="24">
            <a href="/justmoon">justmoon</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Justin Soliz" data-user="431277" height="24" src="https://avatars2.githubusercontent.com/u/431277?v=3&amp;s=48" width="24">
            <a href="/justinsoliz">justinsoliz</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="John Mumm" data-user="4730316" height="24" src="https://avatars0.githubusercontent.com/u/4730316?v=3&amp;s=48" width="24">
            <a href="/jtfmumm">jtfmumm</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Joseandro Luiz" data-user="900097" height="24" src="https://avatars1.githubusercontent.com/u/900097?v=3&amp;s=48" width="24">
            <a href="/joseandro">joseandro</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Jose Joaquin Merino" data-user="3129507" height="24" src="https://avatars3.githubusercontent.com/u/3129507?v=3&amp;s=48" width="24">
            <a href="/jjmerino">jjmerino</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Robert Djurasaj" data-user="31543" height="24" src="https://avatars3.githubusercontent.com/u/31543?v=3&amp;s=48" width="24">
            <a href="/robertd">robertd</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Jelle Kralt" data-user="214558" height="24" src="https://avatars1.githubusercontent.com/u/214558?v=3&amp;s=48" width="24">
            <a href="/jellekralt">jellekralt</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="JD Hartley" data-user="405538" height="24" src="https://avatars3.githubusercontent.com/u/405538?v=3&amp;s=48" width="24">
            <a href="/jdhartley">jdhartley</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Jason Edelman" data-user="453402" height="24" src="https://avatars0.githubusercontent.com/u/453402?v=3&amp;s=48" width="24">
            <a href="/ultimatedelman">ultimatedelman</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Ulysse Carion" data-user="2180153" height="24" src="https://avatars2.githubusercontent.com/u/2180153?v=3&amp;s=48" width="24">
            <a href="/ucarion">ucarion</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Serg" data-user="1378452" height="24" src="https://avatars0.githubusercontent.com/u/1378452?v=3&amp;s=48" width="24">
            <a href="/sbezludny">sbezludny</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Jacob Gable" data-user="164497" height="24" src="https://avatars1.githubusercontent.com/u/164497?v=3&amp;s=48" width="24">
            <a href="/jgable">jgable</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="SiPlus" data-user="1764343" height="24" src="https://avatars3.githubusercontent.com/u/1764343?v=3&amp;s=48" width="24">
            <a href="/SiPlus">SiPlus</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Ryun Shofner" data-user="227672" height="24" src="https://avatars0.githubusercontent.com/u/227672?v=3&amp;s=48" width="24">
            <a href="/ryun">ryun</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Horace Ko" data-user="698456" height="24" src="https://avatars3.githubusercontent.com/u/698456?v=3&amp;s=48" width="24">
            <a href="/horaceko">horaceko</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Vitaly" data-user="1676506" height="24" src="https://avatars0.githubusercontent.com/u/1676506?v=3&amp;s=48" width="24">
            <a href="/Laboratory">Laboratory</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Bishop Zareh" data-user="1138587" height="24" src="https://avatars2.githubusercontent.com/u/1138587?v=3&amp;s=48" width="24">
            <a href="/bishopZ">bishopZ</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Gabriel Pedro" data-user="2898638" height="24" src="https://avatars1.githubusercontent.com/u/2898638?v=3&amp;s=48" width="24">
            <a href="/gpedro">gpedro</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="PatrickJS" data-user="1016365" height="24" src="https://avatars0.githubusercontent.com/u/1016365?v=3&amp;s=48" width="24">
            <a href="/gdi2290">gdi2290</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="徐迪行" data-user="2238823" height="24" src="https://avatars1.githubusercontent.com/u/2238823?v=3&amp;s=48" width="24">
            <a href="/DeanXu">DeanXu</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="oslek" data-user="3261459" height="24" src="https://avatars2.githubusercontent.com/u/3261459?v=3&amp;s=48" width="24">
            <a href="/oslek">oslek</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Gareth Visagie" data-user="418277" height="24" src="https://avatars3.githubusercontent.com/u/418277?v=3&amp;s=48" width="24">
            <a href="/gjvis">gjvis</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Francis Plaza" data-user="1321967" height="24" src="https://avatars2.githubusercontent.com/u/1321967?v=3&amp;s=48" width="24">
            <a href="/FrancisPlaza">FrancisPlaza</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Francesc Puig" data-user="1686499" height="24" src="https://avatars1.githubusercontent.com/u/1686499?v=3&amp;s=48" width="24">
            <a href="/fpmweb">fpmweb</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Flurin Egger" data-user="20311" height="24" src="https://avatars3.githubusercontent.com/u/20311?v=3&amp;s=48" width="24">
            <a href="/flurin">flurin</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Omar Duarte" data-user="4765697" height="24" src="https://avatars1.githubusercontent.com/u/4765697?v=3&amp;s=48" width="24">
            <a href="/omarduarte">omarduarte</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Feoktistov Mihail" data-user="251913" height="24" src="https://avatars1.githubusercontent.com/u/251913?v=3&amp;s=48" width="24">
            <a href="/zealotous">zealotous</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Davy Chiu" data-user="787477" height="24" src="https://avatars3.githubusercontent.com/u/787477?v=3&amp;s=48" width="24">
            <a href="/davychiu">davychiu</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Dan Phillimore" data-user="1714005" height="24" src="https://avatars2.githubusercontent.com/u/1714005?v=3&amp;s=48" width="24">
            <a href="/asmblah">asmblah</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Vsevolod Rodionov" data-user="1269512" height="24" src="https://avatars2.githubusercontent.com/u/1269512?v=3&amp;s=48" width="24">
            <a href="/Jabher">Jabher</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Markus Hedlund" data-user="168042" height="24" src="https://avatars2.githubusercontent.com/u/168042?v=3&amp;s=48" width="24">
            <a href="/Znarkus">Znarkus</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Carlos Andres Herrera" data-user="1084920" height="24" src="https://avatars0.githubusercontent.com/u/1084920?v=3&amp;s=48" width="24">
            <a href="/caherrerapa">caherrerapa</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Max Goodman" data-user="16893" height="24" src="https://avatars3.githubusercontent.com/u/16893?v=3&amp;s=48" width="24">
            <a href="/chromakode">chromakode</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Ben Morrall" data-user="558455" height="24" src="https://avatars0.githubusercontent.com/u/558455?v=3&amp;s=48" width="24">
            <a href="/bmorrall">bmorrall</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Ahmed Aeon Axan" data-user="1500309" height="24" src="https://avatars1.githubusercontent.com/u/1500309?v=3&amp;s=48" width="24">
            <a href="/AeonAxan">AeonAxan</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Arthur Moura Carvalho" data-user="1134016" height="24" src="https://avatars2.githubusercontent.com/u/1134016?v=3&amp;s=48" width="24">
            <a href="/armoucar">armoucar</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Andrew Teich" data-user="4775201" height="24" src="https://avatars2.githubusercontent.com/u/4775201?v=3&amp;s=48" width="24">
            <a href="/ateich">ateich</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Andreas Savvides" data-user="2316326" height="24" src="https://avatars2.githubusercontent.com/u/2316326?v=3&amp;s=48" width="24">
            <a href="/AnSavvides">AnSavvides</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Allan Bettarel" data-user="3026891" height="24" src="https://avatars2.githubusercontent.com/u/3026891?v=3&amp;s=48" width="24">
            <a href="/chilipote">chilipote</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Alexandre Assouad" data-user="498106" height="24" src="https://avatars0.githubusercontent.com/u/498106?v=3&amp;s=48" width="24">
            <a href="/t0k4rt">t0k4rt</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Alex Jeng" data-user="4458931" height="24" src="https://avatars3.githubusercontent.com/u/4458931?v=3&amp;s=48" width="24">
            <a href="/AlexJeng">AlexJeng</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Jack Lawson" data-user="175515" height="24" src="https://avatars1.githubusercontent.com/u/175515?v=3&amp;s=48" width="24">
            <a href="/ajacksified">ajacksified</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Adrian Bruinhout" data-user="1121418" height="24" src="https://avatars3.githubusercontent.com/u/1121418?v=3&amp;s=48" width="24">
            <a href="/webfella">webfella</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="Adam Alexander" data-user="50389" height="24" src="https://avatars2.githubusercontent.com/u/50389?v=3&amp;s=48" width="24">
            <a href="/adamalex">adamalex</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
    <div class="file-actions">
      <div class="button-group">
        <a href="/airbnb/javascript/raw/master/README.md" class="minibutton " id="raw-url">Raw</a>
          <a href="/airbnb/javascript/blame/master/README.md" class="minibutton js-update-url-with-hash">Blame</a>
        <a href="/airbnb/javascript/commits/master/README.md" class="minibutton " rel="nofollow">History</a>
      </div><!-- /.button-group -->

        <a class="octicon-button tooltipped tooltipped-nw" href="github-windows://openRepo/https://github.com/airbnb/javascript?branch=master&amp;filepath=README.md" aria-label="Open this file in GitHub for Windows">
            <span class="octicon octicon-device-desktop"></span>
        </a>

            <form accept-charset="UTF-8" action="/airbnb/javascript/edit/master/README.md" aria-label="Clicking this button will fork this project so you can edit the file" class="tooltipped tooltipped-s inline-form edit-file-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="✓"><input name="authenticity_token" type="hidden" value="yMWcNc9t45F1Qc+UwYa9JhoIXBNYbdYNvNqxcwuYiesbLWCWKIrQw4nk9kduqUiNHOMj5WHFMY+4bBVRLaup8Q=="></div>
              <button class="web-edit-button" type="submit" data-hotkey="e" data-disable-with="">
                <span class="octicon octicon-pencil"></span>
              </button>
</form>
          <form accept-charset="UTF-8" action="/airbnb/javascript/delete/master/README.md" aria-label="Fork this project and delete file" class="tooltipped tooltipped-s inline-form delete-file-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="✓"><input name="authenticity_token" type="hidden" value="vl/va99Ske02ouy2ad8jFtx+F3v9MbEwcnvtgbeyfP7meU8nQrQ6aNfoWK8Tz9GXkdNzZ4t9HKYGhH6cY8pEBg=="></div>
            <button class="web-edit-button" type="submit" data-disable-with="">
              <span class="octicon octicon-trashcan "></span>
            </button>
</form>      
    </div><!-- /.actions -->
    <div class="file-info">
        1701 lines (1263 sloc)
        <span class="file-info-divider"></span>
      44.284 kb
    </div>
  </div>
    <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><p><a href="https://gitter.im/airbnb/javascript?utm_source=badge&amp;utm_medium=badge&amp;utm_campaign=pr-badge"><img src="https://camo.githubusercontent.com/da2edb525cde1455a622c58c0effc3a90b9a181c/68747470733a2f2f6261646765732e6769747465722e696d2f4a6f696e253230436861742e737667" alt="Gitter" data-canonical-src="https://badges.gitter.im/Join%20Chat.svg" style="max-width:100%;"></a></p>

<h1>
<a id="user-content-airbnb-javascript-style-guide-" class="anchor" href="#airbnb-javascript-style-guide-" aria-hidden="true"><span class="octicon octicon-link"></span></a>Airbnb JavaScript Style Guide() {</h1>

<p><em>A mostly reasonable approach to JavaScript</em></p>

<h2>
<a id="user-content-table-of-contents" class="anchor" href="#table-of-contents" aria-hidden="true"><span class="octicon octicon-link"></span></a>Table of Contents</h2>

<ol class="task-list">
<li><a href="#types">Types</a></li>
<li><a href="#objects">Objects</a></li>
<li><a href="#arrays">Arrays</a></li>
<li><a href="#strings">Strings</a></li>
<li><a href="#functions">Functions</a></li>
<li><a href="#properties">Properties</a></li>
<li><a href="#variables">Variables</a></li>
<li><a href="#hoisting">Hoisting</a></li>
<li><a href="#conditional-expressions--equality">Conditional Expressions &amp; Equality</a></li>
<li><a href="#blocks">Blocks</a></li>
<li><a href="#comments">Comments</a></li>
<li><a href="#whitespace">Whitespace</a></li>
<li><a href="#commas">Commas</a></li>
<li><a href="#semicolons">Semicolons</a></li>
<li><a href="#type-casting--coercion">Type Casting &amp; Coercion</a></li>
<li><a href="#naming-conventions">Naming Conventions</a></li>
<li><a href="#accessors">Accessors</a></li>
<li><a href="#constructors">Constructors</a></li>
<li><a href="#events">Events</a></li>
<li><a href="#modules">Modules</a></li>
<li><a href="#jquery">jQuery</a></li>
<li><a href="#ecmascript-5-compatibility">ECMAScript 5 Compatibility</a></li>
<li><a href="#testing">Testing</a></li>
<li><a href="#performance">Performance</a></li>
<li><a href="#resources">Resources</a></li>
<li><a href="#in-the-wild">In the Wild</a></li>
<li><a href="#translation">Translation</a></li>
<li><a href="#the-javascript-style-guide-guide">The JavaScript Style Guide Guide</a></li>
<li><a href="#chat-with-us-about-javascript">Chat With Us About Javascript</a></li>
<li><a href="#contributors">Contributors</a></li>
<li><a href="#license">License</a></li>
</ol>

<h2>
<a id="user-content-types" class="anchor" href="#types" aria-hidden="true"><span class="octicon octicon-link"></span></a>Types</h2>

<ul class="task-list">
<li>
<p><strong>Primitives</strong>: When you access a primitive type you work directly on its value.</p>

<ul class="task-list">
<li><code>string</code></li>
<li><code>number</code></li>
<li><code>boolean</code></li>
<li><code>null</code></li>
<li><code>undefined</code></li>
</ul>

<div class="highlight highlight-javascript"><pre><span class="pl-s">var</span> foo <span class="pl-k">=</span> <span class="pl-c1">1</span>;
<span class="pl-s">var</span> bar <span class="pl-k">=</span> foo;

bar <span class="pl-k">=</span> <span class="pl-c1">9</span>;

<span class="pl-en">console</span><span class="pl-s3">.log</span>(foo, bar); <span class="pl-c">// =&gt; 1, 9</span></pre></div>
</li>
<li>
<p><strong>Complex</strong>: When you access a complex type you work on a reference to its value.</p>

<ul class="task-list">
<li><code>object</code></li>
<li><code>array</code></li>
<li><code>function</code></li>
</ul>

<div class="highlight highlight-javascript"><pre><span class="pl-s">var</span> foo <span class="pl-k">=</span> [<span class="pl-c1">1</span>, <span class="pl-c1">2</span>];
<span class="pl-s">var</span> bar <span class="pl-k">=</span> foo;

bar[<span class="pl-c1">0</span>] <span class="pl-k">=</span> <span class="pl-c1">9</span>;

<span class="pl-en">console</span><span class="pl-s3">.log</span>(foo[<span class="pl-c1">0</span>], bar[<span class="pl-c1">0</span>]); <span class="pl-c">// =&gt; 9, 9</span></pre></div>
</li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-objects" class="anchor" href="#objects" aria-hidden="true"><span class="octicon octicon-link"></span></a>Objects</h2>

<ul class="task-list">
<li>
<p>Use the literal syntax for object creation.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-s">var</span> item <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">Object</span>();

<span class="pl-c">// good</span>
<span class="pl-s">var</span> item <span class="pl-k">=</span> {};</pre></div>
</li>
<li>
<p>Don't use <a href="http://es5.github.io/#x7.6.1">reserved words</a> as keys. It won't work in IE8. <a href="https://github.com/airbnb/javascript/issues/61">More info</a>.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-s">var</span> superman <span class="pl-k">=</span> {
  <span class="pl-k">default</span><span class="pl-k">:</span> { clark<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>kent<span class="pl-pds">'</span></span> },
  private<span class="pl-k">:</span> <span class="pl-c1">true</span>
};

<span class="pl-c">// good</span>
<span class="pl-s">var</span> superman <span class="pl-k">=</span> {
  defaults<span class="pl-k">:</span> { clark<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>kent<span class="pl-pds">'</span></span> },
  hidden<span class="pl-k">:</span> <span class="pl-c1">true</span>
};</pre></div>
</li>
<li>
<p>Use readable synonyms in place of reserved words.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-s">var</span> superman <span class="pl-k">=</span> {
  class<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>alien<span class="pl-pds">'</span></span>
};

<span class="pl-c">// bad</span>
<span class="pl-s">var</span> superman <span class="pl-k">=</span> {
  klass<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>alien<span class="pl-pds">'</span></span>
};

<span class="pl-c">// good</span>
<span class="pl-s">var</span> superman <span class="pl-k">=</span> {
  type<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>alien<span class="pl-pds">'</span></span>
};</pre></div>
</li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-arrays" class="anchor" href="#arrays" aria-hidden="true"><span class="octicon octicon-link"></span></a>Arrays</h2>

<ul class="task-list">
<li>
<p>Use the literal syntax for array creation.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-s">var</span> items <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">Array</span>();

<span class="pl-c">// good</span>
<span class="pl-s">var</span> items <span class="pl-k">=</span> [];</pre></div>
</li>
<li>
<p>If you don't know array length use Array#push.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-s">var</span> someStack <span class="pl-k">=</span> [];


<span class="pl-c">// bad</span>
someStack[someStack.<span class="pl-sc">length</span>] <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">'</span>abracadabra<span class="pl-pds">'</span></span>;

<span class="pl-c">// good</span>
someStack.<span class="pl-s3">push</span>(<span class="pl-s1"><span class="pl-pds">'</span>abracadabra<span class="pl-pds">'</span></span>);</pre></div>
</li>
<li>
<p>When you need to copy an array use Array#slice. <a href="http://jsperf.com/converting-arguments-to-an-array/7">jsPerf</a></p>

<div class="highlight highlight-javascript"><pre><span class="pl-s">var</span> len <span class="pl-k">=</span> items.<span class="pl-sc">length</span>;
<span class="pl-s">var</span> itemsCopy <span class="pl-k">=</span> [];
<span class="pl-s">var</span> i;

<span class="pl-c">// bad</span>
<span class="pl-k">for</span> (i <span class="pl-k">=</span> <span class="pl-c1">0</span>; i <span class="pl-k">&lt;</span> len; i<span class="pl-k">++</span>) {
  itemsCopy[i] <span class="pl-k">=</span> items[i];
}

<span class="pl-c">// good</span>
itemsCopy <span class="pl-k">=</span> items.<span class="pl-s3">slice</span>();</pre></div>
</li>
<li>
<p>To convert an array-like object to an array, use Array#slice.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-st">function</span> <span class="pl-en">trigger</span>() {
  <span class="pl-s">var</span> args <span class="pl-k">=</span> <span class="pl-s3">Array</span>.<span class="pl-sc">prototype</span>.slice.<span class="pl-s3">call</span>(arguments);
  ...
}</pre></div>
</li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-strings" class="anchor" href="#strings" aria-hidden="true"><span class="octicon octicon-link"></span></a>Strings</h2>

<ul class="task-list">
<li>
<p>Use single quotes <code>''</code> for strings.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-s">var</span> name <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>Bob Parr<span class="pl-pds">"</span></span>;

<span class="pl-c">// good</span>
<span class="pl-s">var</span> name <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">'</span>Bob Parr<span class="pl-pds">'</span></span>;

<span class="pl-c">// bad</span>
<span class="pl-s">var</span> fullName <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>Bob <span class="pl-pds">"</span></span> <span class="pl-k">+</span> <span class="pl-v">this</span>.lastName;

<span class="pl-c">// good</span>
<span class="pl-s">var</span> fullName <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">'</span>Bob <span class="pl-pds">'</span></span> <span class="pl-k">+</span> <span class="pl-v">this</span>.lastName;</pre></div>
</li>
<li><p>Strings longer than 80 characters should be written across multiple lines using string concatenation.</p></li>
<li>
<p>Note: If overused, long strings with concatenation could impact performance. <a href="http://jsperf.com/ya-string-concat">jsPerf</a> &amp; <a href="https://github.com/airbnb/javascript/issues/40">Discussion</a>.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-s">var</span> errorMessage <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">'</span>This is a super long error that was thrown because of Batman. When you stop to think about how Batman had anything to do with this, you would get nowhere fast.<span class="pl-pds">'</span></span>;

<span class="pl-c">// bad</span>
<span class="pl-s">var</span> errorMessage <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">'</span>This is a super long error that was thrown because \</span>
<span class="pl-s1">of Batman. When you stop to think about how Batman had anything to do \</span>
<span class="pl-s1">with this, you would get nowhere \</span>
<span class="pl-s1">fast.<span class="pl-pds">'</span></span>;

<span class="pl-c">// good</span>
<span class="pl-s">var</span> errorMessage <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">'</span>This is a super long error that was thrown because <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
  <span class="pl-s1"><span class="pl-pds">'</span>of Batman. When you stop to think about how Batman had anything to do <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
  <span class="pl-s1"><span class="pl-pds">'</span>with this, you would get nowhere fast.<span class="pl-pds">'</span></span>;</pre></div>
</li>
<li>
<p>When programmatically building up a string, use Array#join instead of string concatenation. Mostly for IE: <a href="http://jsperf.com/string-vs-array-concat/2">jsPerf</a>.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-s">var</span> items;
<span class="pl-s">var</span> messages;
<span class="pl-s">var</span> length;
<span class="pl-s">var</span> i;

messages <span class="pl-k">=</span> [{
  state<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>success<span class="pl-pds">'</span></span>,
  message<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>This one worked.<span class="pl-pds">'</span></span>
}, {
  state<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>success<span class="pl-pds">'</span></span>,
  message<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>This one worked as well.<span class="pl-pds">'</span></span>
}, {
  state<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>error<span class="pl-pds">'</span></span>,
  message<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>This one did not work.<span class="pl-pds">'</span></span>
}];

length <span class="pl-k">=</span> messages.<span class="pl-sc">length</span>;

<span class="pl-c">// bad</span>
<span class="pl-st">function</span> <span class="pl-en">inbox</span>(<span class="pl-vpf">messages</span>) {
  items <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">'</span>&lt;ul&gt;<span class="pl-pds">'</span></span>;

  <span class="pl-k">for</span> (i <span class="pl-k">=</span> <span class="pl-c1">0</span>; i <span class="pl-k">&lt;</span> length; i<span class="pl-k">++</span>) {
    items <span class="pl-k">+=</span> <span class="pl-s1"><span class="pl-pds">'</span>&lt;li&gt;<span class="pl-pds">'</span></span> <span class="pl-k">+</span> messages[i].message <span class="pl-k">+</span> <span class="pl-s1"><span class="pl-pds">'</span>&lt;/li&gt;<span class="pl-pds">'</span></span>;
  }

  <span class="pl-k">return</span> items <span class="pl-k">+</span> <span class="pl-s1"><span class="pl-pds">'</span>&lt;/ul&gt;<span class="pl-pds">'</span></span>;
}

<span class="pl-c">// good</span>
<span class="pl-st">function</span> <span class="pl-en">inbox</span>(<span class="pl-vpf">messages</span>) {
  items <span class="pl-k">=</span> [];

  <span class="pl-k">for</span> (i <span class="pl-k">=</span> <span class="pl-c1">0</span>; i <span class="pl-k">&lt;</span> length; i<span class="pl-k">++</span>) {
    items[i] <span class="pl-k">=</span> messages[i].message;
  }

  <span class="pl-k">return</span> <span class="pl-s1"><span class="pl-pds">'</span>&lt;ul&gt;&lt;li&gt;<span class="pl-pds">'</span></span> <span class="pl-k">+</span> items.<span class="pl-s3">join</span>(<span class="pl-s1"><span class="pl-pds">'</span>&lt;/li&gt;&lt;li&gt;<span class="pl-pds">'</span></span>) <span class="pl-k">+</span> <span class="pl-s1"><span class="pl-pds">'</span>&lt;/li&gt;&lt;/ul&gt;<span class="pl-pds">'</span></span>;
}</pre></div>
</li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-functions" class="anchor" href="#functions" aria-hidden="true"><span class="octicon octicon-link"></span></a>Functions</h2>

<ul class="task-list">
<li>
<p>Function expressions:</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// anonymous function expression</span>
<span class="pl-s">var</span> <span class="pl-en">anonymous</span> <span class="pl-k">=</span> <span class="pl-st">function</span>() {
  <span class="pl-k">return</span> <span class="pl-c1">true</span>;
};

<span class="pl-c">// named function expression</span>
<span class="pl-s">var</span> named <span class="pl-k">=</span> <span class="pl-st">function</span> <span class="pl-en">named</span>() {
  <span class="pl-k">return</span> <span class="pl-c1">true</span>;
};

<span class="pl-c">// immediately-invoked function expression (IIFE)</span>
(<span class="pl-st">function</span>() {
  <span class="pl-en">console</span><span class="pl-s3">.log</span>(<span class="pl-s1"><span class="pl-pds">'</span>Welcome to the Internet. Please follow me.<span class="pl-pds">'</span></span>);
})();</pre></div>
</li>
<li><p>Never declare a function in a non-function block (if, while, etc). Assign the function to a variable instead. Browsers will allow you to do it, but they all interpret it differently, which is bad news bears.</p></li>
<li>
<p><strong>Note:</strong> ECMA-262 defines a <code>block</code> as a list of statements. A function declaration is not a statement. <a href="http://www.ecma-international.org/publications/files/ECMA-ST/Ecma-262.pdf#page=97">Read ECMA-262's note on this issue</a>.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">if</span> (currentUser) {
  <span class="pl-st">function</span> <span class="pl-en">test</span>() {
    <span class="pl-en">console</span><span class="pl-s3">.log</span>(<span class="pl-s1"><span class="pl-pds">'</span>Nope.<span class="pl-pds">'</span></span>);
  }
}

<span class="pl-c">// good</span>
<span class="pl-s">var</span> test;
<span class="pl-k">if</span> (currentUser) {
  test <span class="pl-k">=</span> <span class="pl-st">function</span> <span class="pl-en">test</span>() {
    <span class="pl-en">console</span><span class="pl-s3">.log</span>(<span class="pl-s1"><span class="pl-pds">'</span>Yup.<span class="pl-pds">'</span></span>);
  };
}</pre></div>
</li>
<li>
<p>Never name a parameter <code>arguments</code>, this will take precedence over the <code>arguments</code> object that is given to every function scope.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-st">function</span> <span class="pl-en">nope</span>(<span class="pl-vpf">name</span>, <span class="pl-vpf">options</span>, <span class="pl-vpf">arguments</span>) {
  <span class="pl-c">// ...stuff...</span>
}

<span class="pl-c">// good</span>
<span class="pl-st">function</span> <span class="pl-en">yup</span>(<span class="pl-vpf">name</span>, <span class="pl-vpf">options</span>, <span class="pl-vpf">args</span>) {
  <span class="pl-c">// ...stuff...</span>
}</pre></div>
</li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-properties" class="anchor" href="#properties" aria-hidden="true"><span class="octicon octicon-link"></span></a>Properties</h2>

<ul class="task-list">
<li>
<p>Use dot notation when accessing properties.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-s">var</span> luke <span class="pl-k">=</span> {
  jedi<span class="pl-k">:</span> <span class="pl-c1">true</span>,
  age<span class="pl-k">:</span> <span class="pl-c1">28</span>
};

<span class="pl-c">// bad</span>
<span class="pl-s">var</span> isJedi <span class="pl-k">=</span> luke[<span class="pl-s1"><span class="pl-pds">'</span>jedi<span class="pl-pds">'</span></span>];

<span class="pl-c">// good</span>
<span class="pl-s">var</span> isJedi <span class="pl-k">=</span> luke.jedi;</pre></div>
</li>
<li>
<p>Use subscript notation <code>[]</code> when accessing properties with a variable.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-s">var</span> luke <span class="pl-k">=</span> {
  jedi<span class="pl-k">:</span> <span class="pl-c1">true</span>,
  age<span class="pl-k">:</span> <span class="pl-c1">28</span>
};

<span class="pl-st">function</span> <span class="pl-en">getProp</span>(<span class="pl-vpf">prop</span>) {
  <span class="pl-k">return</span> luke[prop];
}

<span class="pl-s">var</span> isJedi <span class="pl-k">=</span> getProp(<span class="pl-s1"><span class="pl-pds">'</span>jedi<span class="pl-pds">'</span></span>);</pre></div>
</li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-variables" class="anchor" href="#variables" aria-hidden="true"><span class="octicon octicon-link"></span></a>Variables</h2>

<ul class="task-list">
<li>
<p>Always use <code>var</code> to declare variables. Not doing so will result in global variables. We want to avoid polluting the global namespace. Captain Planet warned us of that.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
superPower <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">SuperPower</span>();

<span class="pl-c">// good</span>
<span class="pl-s">var</span> superPower <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">SuperPower</span>();</pre></div>
</li>
<li>
<p>Use one <code>var</code> declaration per variable.
It's easier to add new variable declarations this way, and you never have
to worry about swapping out a <code>;</code> for a <code>,</code> or introducing punctuation-only
diffs.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-s">var</span> items <span class="pl-k">=</span> getItems(),
    goSportsTeam <span class="pl-k">=</span> <span class="pl-c1">true</span>,
    dragonball <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">'</span>z<span class="pl-pds">'</span></span>;

<span class="pl-c">// bad</span>
<span class="pl-c">// (compare to above, and try to spot the mistake)</span>
<span class="pl-s">var</span> items <span class="pl-k">=</span> getItems(),
    goSportsTeam <span class="pl-k">=</span> <span class="pl-c1">true</span>;
    dragonball <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">'</span>z<span class="pl-pds">'</span></span>;

<span class="pl-c">// good</span>
<span class="pl-s">var</span> items <span class="pl-k">=</span> getItems();
<span class="pl-s">var</span> goSportsTeam <span class="pl-k">=</span> <span class="pl-c1">true</span>;
<span class="pl-s">var</span> dragonball <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">'</span>z<span class="pl-pds">'</span></span>;</pre></div>
</li>
<li>
<p>Declare unassigned variables last. This is helpful when later on you might need to assign a variable depending on one of the previous assigned variables.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-s">var</span> i, len, dragonball,
    items <span class="pl-k">=</span> getItems(),
    goSportsTeam <span class="pl-k">=</span> <span class="pl-c1">true</span>;

<span class="pl-c">// bad</span>
<span class="pl-s">var</span> i;
<span class="pl-s">var</span> items <span class="pl-k">=</span> getItems();
<span class="pl-s">var</span> dragonball;
<span class="pl-s">var</span> goSportsTeam <span class="pl-k">=</span> <span class="pl-c1">true</span>;
<span class="pl-s">var</span> len;

<span class="pl-c">// good</span>
<span class="pl-s">var</span> items <span class="pl-k">=</span> getItems();
<span class="pl-s">var</span> goSportsTeam <span class="pl-k">=</span> <span class="pl-c1">true</span>;
<span class="pl-s">var</span> dragonball;
<span class="pl-s">var</span> length;
<span class="pl-s">var</span> i;</pre></div>
</li>
<li>
<p>Assign variables at the top of their scope. This helps avoid issues with variable declaration and assignment hoisting related issues.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-st">function</span>() {
  <span class="pl-s3">test</span>();
  <span class="pl-en">console</span><span class="pl-s3">.log</span>(<span class="pl-s1"><span class="pl-pds">'</span>doing stuff..<span class="pl-pds">'</span></span>);

  <span class="pl-c">//..other stuff..</span>

  <span class="pl-s">var</span> name <span class="pl-k">=</span> getName();

  <span class="pl-k">if</span> (name <span class="pl-k">===</span> <span class="pl-s1"><span class="pl-pds">'</span>test<span class="pl-pds">'</span></span>) {
    <span class="pl-k">return</span> <span class="pl-c1">false</span>;
  }

  <span class="pl-k">return</span> name;
}

<span class="pl-c">// good</span>
<span class="pl-st">function</span>() {
  <span class="pl-s">var</span> name <span class="pl-k">=</span> getName();

  <span class="pl-s3">test</span>();
  <span class="pl-en">console</span><span class="pl-s3">.log</span>(<span class="pl-s1"><span class="pl-pds">'</span>doing stuff..<span class="pl-pds">'</span></span>);

  <span class="pl-c">//..other stuff..</span>

  <span class="pl-k">if</span> (name <span class="pl-k">===</span> <span class="pl-s1"><span class="pl-pds">'</span>test<span class="pl-pds">'</span></span>) {
    <span class="pl-k">return</span> <span class="pl-c1">false</span>;
  }

  <span class="pl-k">return</span> name;
}

<span class="pl-c">// bad</span>
<span class="pl-st">function</span>() {
  <span class="pl-s">var</span> name <span class="pl-k">=</span> getName();

  <span class="pl-k">if</span> (<span class="pl-k">!</span>arguments.<span class="pl-sc">length</span>) {
    <span class="pl-k">return</span> <span class="pl-c1">false</span>;
  }

  <span class="pl-k">return</span> <span class="pl-c1">true</span>;
}

<span class="pl-c">// good</span>
<span class="pl-st">function</span>() {
  <span class="pl-k">if</span> (<span class="pl-k">!</span>arguments.<span class="pl-sc">length</span>) {
    <span class="pl-k">return</span> <span class="pl-c1">false</span>;
  }

  <span class="pl-s">var</span> name <span class="pl-k">=</span> getName();

  <span class="pl-k">return</span> <span class="pl-c1">true</span>;
}</pre></div>
</li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-hoisting" class="anchor" href="#hoisting" aria-hidden="true"><span class="octicon octicon-link"></span></a>Hoisting</h2>

<ul class="task-list">
<li>
<p>Variable declarations get hoisted to the top of their scope, their assignment does not.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// we know this wouldn't work (assuming there</span>
<span class="pl-c">// is no notDefined global variable)</span>
<span class="pl-st">function</span> <span class="pl-en">example</span>() {
  <span class="pl-en">console</span><span class="pl-s3">.log</span>(notDefined); <span class="pl-c">// =&gt; throws a ReferenceError</span>
}

<span class="pl-c">// creating a variable declaration after you</span>
<span class="pl-c">// reference the variable will work due to</span>
<span class="pl-c">// variable hoisting. Note: the assignment</span>
<span class="pl-c">// value of `true` is not hoisted.</span>
<span class="pl-st">function</span> <span class="pl-en">example</span>() {
  <span class="pl-en">console</span><span class="pl-s3">.log</span>(declaredButNotAssigned); <span class="pl-c">// =&gt; undefined</span>
  <span class="pl-s">var</span> declaredButNotAssigned <span class="pl-k">=</span> <span class="pl-c1">true</span>;
}

<span class="pl-c">// The interpreter is hoisting the variable</span>
<span class="pl-c">// declaration to the top of the scope,</span>
<span class="pl-c">// which means our example could be rewritten as:</span>
<span class="pl-st">function</span> <span class="pl-en">example</span>() {
  <span class="pl-s">var</span> declaredButNotAssigned;
  <span class="pl-en">console</span><span class="pl-s3">.log</span>(declaredButNotAssigned); <span class="pl-c">// =&gt; undefined</span>
  declaredButNotAssigned <span class="pl-k">=</span> <span class="pl-c1">true</span>;
}</pre></div>
</li>
<li>
<p>Anonymous function expressions hoist their variable name, but not the function assignment.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-st">function</span> <span class="pl-en">example</span>() {
  <span class="pl-en">console</span><span class="pl-s3">.log</span>(anonymous); <span class="pl-c">// =&gt; undefined</span>

  anonymous(); <span class="pl-c">// =&gt; TypeError anonymous is not a function</span>

  <span class="pl-s">var</span> <span class="pl-en">anonymous</span> <span class="pl-k">=</span> <span class="pl-st">function</span>() {
    <span class="pl-en">console</span><span class="pl-s3">.log</span>(<span class="pl-s1"><span class="pl-pds">'</span>anonymous function expression<span class="pl-pds">'</span></span>);
  };
}</pre></div>
</li>
<li>
<p>Named function expressions hoist the variable name, not the function name or the function body.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-st">function</span> <span class="pl-en">example</span>() {
  <span class="pl-en">console</span><span class="pl-s3">.log</span>(named); <span class="pl-c">// =&gt; undefined</span>

  named(); <span class="pl-c">// =&gt; TypeError named is not a function</span>

  superPower(); <span class="pl-c">// =&gt; ReferenceError superPower is not defined</span>

  <span class="pl-s">var</span> named <span class="pl-k">=</span> <span class="pl-st">function</span> <span class="pl-en">superPower</span>() {
    <span class="pl-en">console</span><span class="pl-s3">.log</span>(<span class="pl-s1"><span class="pl-pds">'</span>Flying<span class="pl-pds">'</span></span>);
  };
}

<span class="pl-c">// the same is true when the function name</span>
<span class="pl-c">// is the same as the variable name.</span>
<span class="pl-st">function</span> <span class="pl-en">example</span>() {
  <span class="pl-en">console</span><span class="pl-s3">.log</span>(named); <span class="pl-c">// =&gt; undefined</span>

  named(); <span class="pl-c">// =&gt; TypeError named is not a function</span>

  <span class="pl-s">var</span> named <span class="pl-k">=</span> <span class="pl-st">function</span> <span class="pl-en">named</span>() {
    <span class="pl-en">console</span><span class="pl-s3">.log</span>(<span class="pl-s1"><span class="pl-pds">'</span>named<span class="pl-pds">'</span></span>);
  }
}</pre></div>
</li>
<li>
<p>Function declarations hoist their name and the function body.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-st">function</span> <span class="pl-en">example</span>() {
  superPower(); <span class="pl-c">// =&gt; Flying</span>

  <span class="pl-st">function</span> <span class="pl-en">superPower</span>() {
    <span class="pl-en">console</span><span class="pl-s3">.log</span>(<span class="pl-s1"><span class="pl-pds">'</span>Flying<span class="pl-pds">'</span></span>);
  }
}</pre></div>
</li>
<li><p>For more information refer to <a href="http://www.adequatelygood.com/2010/2/JavaScript-Scoping-and-Hoisting">JavaScript Scoping &amp; Hoisting</a> by <a href="http://www.adequatelygood.com/">Ben Cherry</a>.</p></li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-conditional-expressions--equality" class="anchor" href="#conditional-expressions--equality" aria-hidden="true"><span class="octicon octicon-link"></span></a>Conditional Expressions &amp; Equality</h2>

<ul class="task-list">
<li>Use <code>===</code> and <code>!==</code> over <code>==</code> and <code>!=</code>.</li>
<li>
<p>Conditional expressions are evaluated using coercion with the <code>ToBoolean</code> method and always follow these simple rules:</p>

<ul class="task-list">
<li>
<strong>Objects</strong> evaluate to <strong>true</strong>
</li>
<li>
<strong>Undefined</strong> evaluates to <strong>false</strong>
</li>
<li>
<strong>Null</strong> evaluates to <strong>false</strong>
</li>
<li>
<strong>Booleans</strong> evaluate to <strong>the value of the boolean</strong>
</li>
<li>
<strong>Numbers</strong> evaluate to <strong>false</strong> if <strong>+0, -0, or NaN</strong>, otherwise <strong>true</strong>
</li>
<li>
<strong>Strings</strong> evaluate to <strong>false</strong> if an empty string <code>''</code>, otherwise <strong>true</strong>
</li>
</ul>

<div class="highlight highlight-javascript"><pre><span class="pl-k">if</span> ([<span class="pl-c1">0</span>]) {
  <span class="pl-c">// true</span>
  <span class="pl-c">// An array is an object, objects evaluate to true</span>
}</pre></div>
</li>
<li>
<p>Use shortcuts.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">if</span> (name <span class="pl-k">!==</span> <span class="pl-s1"><span class="pl-pds">'</span><span class="pl-pds">'</span></span>) {
  <span class="pl-c">// ...stuff...</span>
}

<span class="pl-c">// good</span>
<span class="pl-k">if</span> (name) {
  <span class="pl-c">// ...stuff...</span>
}

<span class="pl-c">// bad</span>
<span class="pl-k">if</span> (collection.<span class="pl-sc">length</span> <span class="pl-k">&gt;</span> <span class="pl-c1">0</span>) {
  <span class="pl-c">// ...stuff...</span>
}

<span class="pl-c">// good</span>
<span class="pl-k">if</span> (collection.<span class="pl-sc">length</span>) {
  <span class="pl-c">// ...stuff...</span>
}</pre></div>
</li>
<li><p>For more information see <a href="http://javascriptweblog.wordpress.com/2011/02/07/truth-equality-and-javascript/#more-2108">Truth Equality and JavaScript</a> by Angus Croll.</p></li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-blocks" class="anchor" href="#blocks" aria-hidden="true"><span class="octicon octicon-link"></span></a>Blocks</h2>

<ul class="task-list">
<li>
<p>Use braces with all multi-line blocks.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">if</span> (test)
  <span class="pl-k">return</span> <span class="pl-c1">false</span>;

<span class="pl-c">// good</span>
<span class="pl-k">if</span> (test) <span class="pl-k">return</span> <span class="pl-c1">false</span>;

<span class="pl-c">// good</span>
<span class="pl-k">if</span> (test) {
  <span class="pl-k">return</span> <span class="pl-c1">false</span>;
}

<span class="pl-c">// bad</span>
<span class="pl-st">function</span>() { <span class="pl-k">return</span> <span class="pl-c1">false</span>; }

<span class="pl-c">// good</span>
<span class="pl-st">function</span>() {
  <span class="pl-k">return</span> <span class="pl-c1">false</span>;
}</pre></div>
</li>
<li>
<p>If you're using multi-line blocks with <code>if</code> and <code>else</code>, put <code>else</code> on the same line as your
<code>if</code> block's closing brace.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">if</span> (test) {
  thing1();
  thing2();
}
<span class="pl-k">else</span> {
  thing3();
}

<span class="pl-c">// good</span>
<span class="pl-k">if</span> (test) {
  thing1();
  thing2();
} <span class="pl-k">else</span> {
  thing3();
}</pre></div>
</li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-comments" class="anchor" href="#comments" aria-hidden="true"><span class="octicon octicon-link"></span></a>Comments</h2>

<ul class="task-list">
<li>
<p>Use <code>/** ... */</code> for multiline comments. Include a description, specify types and values for all parameters and return values.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-c">// make() returns a new element</span>
<span class="pl-c">// based on the passed in tag name</span>
<span class="pl-c">//</span>
<span class="pl-c">// @param {String} tag</span>
<span class="pl-c">// @return {Element} element</span>
<span class="pl-st">function</span> <span class="pl-en">make</span>(<span class="pl-vpf">tag</span>) {

  <span class="pl-c">// ...stuff...</span>

  <span class="pl-k">return</span> element;
}

<span class="pl-c">// good</span>
<span class="pl-c">/**</span>
<span class="pl-c"> * make() returns a new element</span>
<span class="pl-c"> * based on the passed in tag name</span>
<span class="pl-c"> *</span>
<span class="pl-c"> * @param {String} tag</span>
<span class="pl-c"> * @return {Element} element</span>
<span class="pl-c"> */</span>
<span class="pl-st">function</span> <span class="pl-en">make</span>(<span class="pl-vpf">tag</span>) {

  <span class="pl-c">// ...stuff...</span>

  <span class="pl-k">return</span> element;
}</pre></div>
</li>
<li>
<p>Use <code>//</code> for single line comments. Place single line comments on a newline above the subject of the comment. Put an empty line before the comment.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-s">var</span> active <span class="pl-k">=</span> <span class="pl-c1">true</span>;  <span class="pl-c">// is current tab</span>

<span class="pl-c">// good</span>
<span class="pl-c">// is current tab</span>
<span class="pl-s">var</span> active <span class="pl-k">=</span> <span class="pl-c1">true</span>;

<span class="pl-c">// bad</span>
<span class="pl-st">function</span> <span class="pl-en">getType</span>() {
  <span class="pl-en">console</span><span class="pl-s3">.log</span>(<span class="pl-s1"><span class="pl-pds">'</span>fetching type...<span class="pl-pds">'</span></span>);
  <span class="pl-c">// set the default type to 'no type'</span>
  <span class="pl-s">var</span> type <span class="pl-k">=</span> <span class="pl-v">this</span>._type <span class="pl-k">||</span> <span class="pl-s1"><span class="pl-pds">'</span>no type<span class="pl-pds">'</span></span>;

  <span class="pl-k">return</span> type;
}

<span class="pl-c">// good</span>
<span class="pl-st">function</span> <span class="pl-en">getType</span>() {
  <span class="pl-en">console</span><span class="pl-s3">.log</span>(<span class="pl-s1"><span class="pl-pds">'</span>fetching type...<span class="pl-pds">'</span></span>);

  <span class="pl-c">// set the default type to 'no type'</span>
  <span class="pl-s">var</span> type <span class="pl-k">=</span> <span class="pl-v">this</span>._type <span class="pl-k">||</span> <span class="pl-s1"><span class="pl-pds">'</span>no type<span class="pl-pds">'</span></span>;

  <span class="pl-k">return</span> type;
}</pre></div>
</li>
<li><p>Prefixing your comments with <code>FIXME</code> or <code>TODO</code> helps other developers quickly understand if you're pointing out a problem that needs to be revisited, or if you're suggesting a solution to the problem that needs to be implemented. These are different than regular comments because they are actionable. The actions are <code>FIXME -- need to figure this out</code> or <code>TODO -- need to implement</code>.</p></li>
<li>
<p>Use <code>// FIXME:</code> to annotate problems.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-st">function</span> <span class="pl-en">Calculator</span>() {

  <span class="pl-c">// FIXME: shouldn't use a global here</span>
  total <span class="pl-k">=</span> <span class="pl-c1">0</span>;

  <span class="pl-k">return</span> <span class="pl-v">this</span>;
}</pre></div>
</li>
<li>
<p>Use <code>// TODO:</code> to annotate solutions to problems.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-st">function</span> <span class="pl-en">Calculator</span>() {

  <span class="pl-c">// TODO: total should be configurable by an options param</span>
  <span class="pl-v">this</span>.total <span class="pl-k">=</span> <span class="pl-c1">0</span>;

  <span class="pl-k">return</span> <span class="pl-v">this</span>;
}</pre></div>
</li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-whitespace" class="anchor" href="#whitespace" aria-hidden="true"><span class="octicon octicon-link"></span></a>Whitespace</h2>

<ul class="task-list">
<li>
<p>Use soft tabs set to 2 spaces.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-st">function</span>() {
∙∙∙∙<span class="pl-s">var</span> name;
}

<span class="pl-c">// bad</span>
<span class="pl-st">function</span>() {
∙<span class="pl-s">var</span> name;
}

<span class="pl-c">// good</span>
<span class="pl-st">function</span>() {
∙∙<span class="pl-s">var</span> name;
}</pre></div>
</li>
<li>
<p>Place 1 space before the leading brace.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-st">function</span> <span class="pl-en">test</span>(){
  <span class="pl-en">console</span><span class="pl-s3">.log</span>(<span class="pl-s1"><span class="pl-pds">'</span>test<span class="pl-pds">'</span></span>);
}

<span class="pl-c">// good</span>
<span class="pl-st">function</span> <span class="pl-en">test</span>() {
  <span class="pl-en">console</span><span class="pl-s3">.log</span>(<span class="pl-s1"><span class="pl-pds">'</span>test<span class="pl-pds">'</span></span>);
}

<span class="pl-c">// bad</span>
dog.set(<span class="pl-s1"><span class="pl-pds">'</span>attr<span class="pl-pds">'</span></span>,{
  age<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>1 year<span class="pl-pds">'</span></span>,
  breed<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>Bernese Mountain Dog<span class="pl-pds">'</span></span>
});

<span class="pl-c">// good</span>
dog.set(<span class="pl-s1"><span class="pl-pds">'</span>attr<span class="pl-pds">'</span></span>, {
  age<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>1 year<span class="pl-pds">'</span></span>,
  breed<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>Bernese Mountain Dog<span class="pl-pds">'</span></span>
});</pre></div>
</li>
<li>
<p>Set off operators with spaces.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-s">var</span> x<span class="pl-k">=</span>y<span class="pl-k">+</span><span class="pl-c1">5</span>;

<span class="pl-c">// good</span>
<span class="pl-s">var</span> x <span class="pl-k">=</span> y <span class="pl-k">+</span> <span class="pl-c1">5</span>;</pre></div>
</li>
<li>
<p>End files with a single newline character.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
(<span class="pl-st">function</span>(<span class="pl-vpf">global</span>) {
  <span class="pl-c">// ...stuff...</span>
})(<span class="pl-v">this</span>);</pre></div>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
(<span class="pl-st">function</span>(<span class="pl-vpf">global</span>) {
  <span class="pl-c">// ...stuff...</span>
})(<span class="pl-v">this</span>);↵
↵</pre></div>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// good</span>
(<span class="pl-st">function</span>(<span class="pl-vpf">global</span>) {
  <span class="pl-c">// ...stuff...</span>
})(<span class="pl-v">this</span>);↵</pre></div>
</li>
<li>
<p>Use indentation when making long method chains. Use a leading dot, which
emphasizes that the line is a method call, not a new statement.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
$(<span class="pl-s1"><span class="pl-pds">'</span>#items<span class="pl-pds">'</span></span>).<span class="pl-s3">find</span>(<span class="pl-s1"><span class="pl-pds">'</span>.selected<span class="pl-pds">'</span></span>).highlight().end().<span class="pl-s3">find</span>(<span class="pl-s1"><span class="pl-pds">'</span>.open<span class="pl-pds">'</span></span>).updateCount();

<span class="pl-c">// bad</span>
$(<span class="pl-s1"><span class="pl-pds">'</span>#items<span class="pl-pds">'</span></span>).
  <span class="pl-s3">find</span>(<span class="pl-s1"><span class="pl-pds">'</span>selected<span class="pl-pds">'</span></span>).
    highlight().
    end().
  <span class="pl-s3">find</span>(<span class="pl-s1"><span class="pl-pds">'</span>.open<span class="pl-pds">'</span></span>).
    updateCount();

<span class="pl-c">// good</span>
$(<span class="pl-s1"><span class="pl-pds">'</span>#items<span class="pl-pds">'</span></span>)
  .<span class="pl-s3">find</span>(<span class="pl-s1"><span class="pl-pds">'</span>.selected<span class="pl-pds">'</span></span>)
    .highlight()
    .end()
  .<span class="pl-s3">find</span>(<span class="pl-s1"><span class="pl-pds">'</span>.open<span class="pl-pds">'</span></span>)
    .updateCount();

<span class="pl-c">// bad</span>
<span class="pl-s">var</span> leds <span class="pl-k">=</span> stage.selectAll(<span class="pl-s1"><span class="pl-pds">'</span>.led<span class="pl-pds">'</span></span>).<span class="pl-sc">data</span>(data).enter().append(<span class="pl-s1"><span class="pl-pds">'</span>svg:svg<span class="pl-pds">'</span></span>).class(<span class="pl-s1"><span class="pl-pds">'</span>led<span class="pl-pds">'</span></span>, <span class="pl-c1">true</span>)
    .attr(<span class="pl-s1"><span class="pl-pds">'</span>width<span class="pl-pds">'</span></span>,  (radius <span class="pl-k">+</span> margin) <span class="pl-k">*</span> <span class="pl-c1">2</span>).append(<span class="pl-s1"><span class="pl-pds">'</span>svg:g<span class="pl-pds">'</span></span>)
    .attr(<span class="pl-s1"><span class="pl-pds">'</span>transform<span class="pl-pds">'</span></span>, <span class="pl-s1"><span class="pl-pds">'</span>translate(<span class="pl-pds">'</span></span> <span class="pl-k">+</span> (radius <span class="pl-k">+</span> margin) <span class="pl-k">+</span> <span class="pl-s1"><span class="pl-pds">'</span>,<span class="pl-pds">'</span></span> <span class="pl-k">+</span> (radius <span class="pl-k">+</span> margin) <span class="pl-k">+</span> <span class="pl-s1"><span class="pl-pds">'</span>)<span class="pl-pds">'</span></span>)
    .<span class="pl-s3">call</span>(tron.led);

<span class="pl-c">// good</span>
<span class="pl-s">var</span> leds <span class="pl-k">=</span> stage.selectAll(<span class="pl-s1"><span class="pl-pds">'</span>.led<span class="pl-pds">'</span></span>)
    .<span class="pl-sc">data</span>(data)
  .enter().append(<span class="pl-s1"><span class="pl-pds">'</span>svg:svg<span class="pl-pds">'</span></span>)
    .class(<span class="pl-s1"><span class="pl-pds">'</span>led<span class="pl-pds">'</span></span>, <span class="pl-c1">true</span>)
    .attr(<span class="pl-s1"><span class="pl-pds">'</span>width<span class="pl-pds">'</span></span>,  (radius <span class="pl-k">+</span> margin) <span class="pl-k">*</span> <span class="pl-c1">2</span>)
  .append(<span class="pl-s1"><span class="pl-pds">'</span>svg:g<span class="pl-pds">'</span></span>)
    .attr(<span class="pl-s1"><span class="pl-pds">'</span>transform<span class="pl-pds">'</span></span>, <span class="pl-s1"><span class="pl-pds">'</span>translate(<span class="pl-pds">'</span></span> <span class="pl-k">+</span> (radius <span class="pl-k">+</span> margin) <span class="pl-k">+</span> <span class="pl-s1"><span class="pl-pds">'</span>,<span class="pl-pds">'</span></span> <span class="pl-k">+</span> (radius <span class="pl-k">+</span> margin) <span class="pl-k">+</span> <span class="pl-s1"><span class="pl-pds">'</span>)<span class="pl-pds">'</span></span>)
    .<span class="pl-s3">call</span>(tron.led);</pre></div>
</li>
<li>
<p>Leave a blank line after blocks and before the next statement</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">if</span> (foo) {
  <span class="pl-k">return</span> bar;
}
<span class="pl-k">return</span> baz;

<span class="pl-c">// good</span>
<span class="pl-k">if</span> (foo) {
  <span class="pl-k">return</span> bar;
}

<span class="pl-k">return</span> baz;

<span class="pl-c">// bad</span>
<span class="pl-s">var</span> obj <span class="pl-k">=</span> {
  <span class="pl-en">foo</span>: <span class="pl-st">function</span>() {
  },
  <span class="pl-en">bar</span>: <span class="pl-st">function</span>() {
  }
};
<span class="pl-k">return</span> obj;

<span class="pl-c">// good</span>
<span class="pl-s">var</span> obj <span class="pl-k">=</span> {
  <span class="pl-en">foo</span>: <span class="pl-st">function</span>() {
  },

  <span class="pl-en">bar</span>: <span class="pl-st">function</span>() {
  }
};

<span class="pl-k">return</span> obj;</pre></div>
</li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-commas" class="anchor" href="#commas" aria-hidden="true"><span class="octicon octicon-link"></span></a>Commas</h2>

<ul class="task-list">
<li>
<p>Leading commas: <strong>Nope.</strong></p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-s">var</span> story <span class="pl-k">=</span> [
    once
  , upon
  , aTime
];

<span class="pl-c">// good</span>
<span class="pl-s">var</span> story <span class="pl-k">=</span> [
  once,
  upon,
  aTime
];

<span class="pl-c">// bad</span>
<span class="pl-s">var</span> hero <span class="pl-k">=</span> {
    firstName<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>Bob<span class="pl-pds">'</span></span>
  , lastName<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>Parr<span class="pl-pds">'</span></span>
  , heroName<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>Mr. Incredible<span class="pl-pds">'</span></span>
  , superPower<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>strength<span class="pl-pds">'</span></span>
};

<span class="pl-c">// good</span>
<span class="pl-s">var</span> hero <span class="pl-k">=</span> {
  firstName<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>Bob<span class="pl-pds">'</span></span>,
  lastName<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>Parr<span class="pl-pds">'</span></span>,
  heroName<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>Mr. Incredible<span class="pl-pds">'</span></span>,
  superPower<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>strength<span class="pl-pds">'</span></span>
};</pre></div>
</li>
<li>
<p>Additional trailing comma: <strong>Nope.</strong> This can cause problems with IE6/7 and IE9 if it's in quirksmode. Also, in some implementations of ES3 would add length to an array if it had an additional trailing comma. This was clarified in ES5 (<a href="http://es5.github.io/#D">source</a>):</p>

<blockquote>
<p>Edition 5 clarifies the fact that a trailing comma at the end of an ArrayInitialiser does not add to the length of the array. This is not a semantic change from Edition 3 but some implementations may have previously misinterpreted this.</p>
</blockquote>

<div class="highlight highlight-javascript"><pre>  <span class="pl-c">// bad</span>
  <span class="pl-s">var</span> hero <span class="pl-k">=</span> {
    firstName<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>Kevin<span class="pl-pds">'</span></span>,
    lastName<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>Flynn<span class="pl-pds">'</span></span>,
  };

  <span class="pl-s">var</span> heroes <span class="pl-k">=</span> [
    <span class="pl-s1"><span class="pl-pds">'</span>Batman<span class="pl-pds">'</span></span>,
    <span class="pl-s1"><span class="pl-pds">'</span>Superman<span class="pl-pds">'</span></span>,
  ];

  <span class="pl-c">// good</span>
  <span class="pl-s">var</span> hero <span class="pl-k">=</span> {
    firstName<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>Kevin<span class="pl-pds">'</span></span>,
    lastName<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>Flynn<span class="pl-pds">'</span></span>
  };

  <span class="pl-s">var</span> heroes <span class="pl-k">=</span> [
    <span class="pl-s1"><span class="pl-pds">'</span>Batman<span class="pl-pds">'</span></span>,
    <span class="pl-s1"><span class="pl-pds">'</span>Superman<span class="pl-pds">'</span></span>
  ];</pre></div>
</li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-semicolons" class="anchor" href="#semicolons" aria-hidden="true"><span class="octicon octicon-link"></span></a>Semicolons</h2>

<ul class="task-list">
<li>
<p><strong>Yup.</strong></p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
(<span class="pl-st">function</span>() {
  <span class="pl-s">var</span> name <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">'</span>Skywalker<span class="pl-pds">'</span></span>
  <span class="pl-k">return</span> name
})()

<span class="pl-c">// good</span>
(<span class="pl-st">function</span>() {
  <span class="pl-s">var</span> name <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">'</span>Skywalker<span class="pl-pds">'</span></span>;
  <span class="pl-k">return</span> name;
})();

<span class="pl-c">// good (guards against the function becoming an argument when two files with IIFEs are concatenated)</span>
;(<span class="pl-st">function</span>() {
  <span class="pl-s">var</span> name <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">'</span>Skywalker<span class="pl-pds">'</span></span>;
  <span class="pl-k">return</span> name;
})();</pre></div>

<p><a href="http://stackoverflow.com/a/7365214/1712802">Read more</a>.</p>
</li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-type-casting--coercion" class="anchor" href="#type-casting--coercion" aria-hidden="true"><span class="octicon octicon-link"></span></a>Type Casting &amp; Coercion</h2>

<ul class="task-list">
<li>Perform type coercion at the beginning of the statement.</li>
<li>
<p>Strings:</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">//  =&gt; this.reviewScore = 9;</span>

<span class="pl-c">// bad</span>
<span class="pl-s">var</span> totalScore <span class="pl-k">=</span> <span class="pl-v">this</span>.reviewScore <span class="pl-k">+</span> <span class="pl-s1"><span class="pl-pds">'</span><span class="pl-pds">'</span></span>;

<span class="pl-c">// good</span>
<span class="pl-s">var</span> totalScore <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">'</span><span class="pl-pds">'</span></span> <span class="pl-k">+</span> <span class="pl-v">this</span>.reviewScore;

<span class="pl-c">// bad</span>
<span class="pl-s">var</span> totalScore <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">'</span><span class="pl-pds">'</span></span> <span class="pl-k">+</span> <span class="pl-v">this</span>.reviewScore <span class="pl-k">+</span> <span class="pl-s1"><span class="pl-pds">'</span> total score<span class="pl-pds">'</span></span>;

<span class="pl-c">// good</span>
<span class="pl-s">var</span> totalScore <span class="pl-k">=</span> <span class="pl-v">this</span>.reviewScore <span class="pl-k">+</span> <span class="pl-s1"><span class="pl-pds">'</span> total score<span class="pl-pds">'</span></span>;</pre></div>
</li>
<li>
<p>Use <code>parseInt</code> for Numbers and always with a radix for type casting.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-s">var</span> inputValue <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">'</span>4<span class="pl-pds">'</span></span>;

<span class="pl-c">// bad</span>
<span class="pl-s">var</span> val <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">Number</span>(inputValue);

<span class="pl-c">// bad</span>
<span class="pl-s">var</span> val <span class="pl-k">=</span> <span class="pl-k">+</span>inputValue;

<span class="pl-c">// bad</span>
<span class="pl-s">var</span> val <span class="pl-k">=</span> inputValue <span class="pl-k">&gt;&gt;</span> <span class="pl-c1">0</span>;

<span class="pl-c">// bad</span>
<span class="pl-s">var</span> val <span class="pl-k">=</span> <span class="pl-s3">parseInt</span>(inputValue);

<span class="pl-c">// good</span>
<span class="pl-s">var</span> val <span class="pl-k">=</span> <span class="pl-s3">Number</span>(inputValue);

<span class="pl-c">// good</span>
<span class="pl-s">var</span> val <span class="pl-k">=</span> <span class="pl-s3">parseInt</span>(inputValue, <span class="pl-c1">10</span>);</pre></div>
</li>
<li>
<p>If for whatever reason you are doing something wild and <code>parseInt</code> is your bottleneck and need to use Bitshift for <a href="http://jsperf.com/coercion-vs-casting/3">performance reasons</a>, leave a comment explaining why and what you're doing.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// good</span>
<span class="pl-c">/**</span>
<span class="pl-c"> * parseInt was the reason my code was slow.</span>
<span class="pl-c"> * Bitshifting the String to coerce it to a</span>
<span class="pl-c"> * Number made it a lot faster.</span>
<span class="pl-c"> */</span>
<span class="pl-s">var</span> val <span class="pl-k">=</span> inputValue <span class="pl-k">&gt;&gt;</span> <span class="pl-c1">0</span>;</pre></div>
</li>
<li>
<p><strong>Note:</strong> Be careful when using bitshift operations. Numbers are represented as <a href="http://es5.github.io/#x4.3.19">64-bit values</a>, but Bitshift operations always return a 32-bit integer (<a href="http://es5.github.io/#x11.7">source</a>). Bitshift can lead to unexpected behavior for integer values larger than 32 bits. <a href="https://github.com/airbnb/javascript/issues/109">Discussion</a>. Largest signed 32-bit Int is 2,147,483,647:</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c1">2147483647</span> <span class="pl-k">&gt;&gt;</span> <span class="pl-c1">0</span> <span class="pl-c">//=&gt; 2147483647</span>
<span class="pl-c1">2147483648</span> <span class="pl-k">&gt;&gt;</span> <span class="pl-c1">0</span> <span class="pl-c">//=&gt; -2147483648</span>
<span class="pl-c1">2147483649</span> <span class="pl-k">&gt;&gt;</span> <span class="pl-c1">0</span> <span class="pl-c">//=&gt; -2147483647</span></pre></div>
</li>
<li>
<p>Booleans:</p>

<div class="highlight highlight-javascript"><pre><span class="pl-s">var</span> age <span class="pl-k">=</span> <span class="pl-c1">0</span>;

<span class="pl-c">// bad</span>
<span class="pl-s">var</span> hasAge <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">Boolean</span>(age);

<span class="pl-c">// good</span>
<span class="pl-s">var</span> hasAge <span class="pl-k">=</span> <span class="pl-s3">Boolean</span>(age);

<span class="pl-c">// good</span>
<span class="pl-s">var</span> hasAge <span class="pl-k">=</span> <span class="pl-k">!!</span>age;</pre></div>
</li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-naming-conventions" class="anchor" href="#naming-conventions" aria-hidden="true"><span class="octicon octicon-link"></span></a>Naming Conventions</h2>

<ul class="task-list">
<li>
<p>Avoid single letter names. Be descriptive with your naming.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-st">function</span> <span class="pl-en">q</span>() {
  <span class="pl-c">// ...stuff...</span>
}

<span class="pl-c">// good</span>
<span class="pl-st">function</span> <span class="pl-en">query</span>() {
  <span class="pl-c">// ..stuff..</span>
}</pre></div>
</li>
<li>
<p>Use camelCase when naming objects, functions, and instances.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-s">var</span> OBJEcttsssss <span class="pl-k">=</span> {};
<span class="pl-s">var</span> this_is_my_object <span class="pl-k">=</span> {};
<span class="pl-st">function</span> <span class="pl-en">c</span>() {}
<span class="pl-s">var</span> u <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">user</span>({
  name<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>Bob Parr<span class="pl-pds">'</span></span>
});

<span class="pl-c">// good</span>
<span class="pl-s">var</span> thisIsMyObject <span class="pl-k">=</span> {};
<span class="pl-st">function</span> <span class="pl-en">thisIsMyFunction</span>() {}
<span class="pl-s">var</span> user <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">User</span>({
  name<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>Bob Parr<span class="pl-pds">'</span></span>
});</pre></div>
</li>
<li>
<p>Use PascalCase when naming constructors or classes.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-st">function</span> <span class="pl-en">user</span>(<span class="pl-vpf">options</span>) {
  <span class="pl-v">this</span>.<span class="pl-sc">name</span> <span class="pl-k">=</span> options.<span class="pl-sc">name</span>;
}

<span class="pl-s">var</span> bad <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">user</span>({
  name<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>nope<span class="pl-pds">'</span></span>
});

<span class="pl-c">// good</span>
<span class="pl-st">function</span> <span class="pl-en">User</span>(<span class="pl-vpf">options</span>) {
  <span class="pl-v">this</span>.<span class="pl-sc">name</span> <span class="pl-k">=</span> options.<span class="pl-sc">name</span>;
}

<span class="pl-s">var</span> good <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">User</span>({
  name<span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>yup<span class="pl-pds">'</span></span>
});</pre></div>
</li>
<li>
<p>Use a leading underscore <code>_</code> when naming private properties.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-v">this</span>.__firstName__ <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">'</span>Panda<span class="pl-pds">'</span></span>;
<span class="pl-v">this</span>.firstName_ <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">'</span>Panda<span class="pl-pds">'</span></span>;

<span class="pl-c">// good</span>
<span class="pl-v">this</span>._firstName <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">'</span>Panda<span class="pl-pds">'</span></span>;</pre></div>
</li>
<li>
<p>When saving a reference to <code>this</code> use <code>_this</code>.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-st">function</span>() {
  <span class="pl-s">var</span> self <span class="pl-k">=</span> <span class="pl-v">this</span>;
  <span class="pl-k">return</span> <span class="pl-st">function</span>() {
    <span class="pl-en">console</span><span class="pl-s3">.log</span>(self);
  };
}

<span class="pl-c">// bad</span>
<span class="pl-st">function</span>() {
  <span class="pl-s">var</span> that <span class="pl-k">=</span> <span class="pl-v">this</span>;
  <span class="pl-k">return</span> <span class="pl-st">function</span>() {
    <span class="pl-en">console</span><span class="pl-s3">.log</span>(that);
  };
}

<span class="pl-c">// good</span>
<span class="pl-st">function</span>() {
  <span class="pl-s">var</span> _this <span class="pl-k">=</span> <span class="pl-v">this</span>;
  <span class="pl-k">return</span> <span class="pl-st">function</span>() {
    <span class="pl-en">console</span><span class="pl-s3">.log</span>(_this);
  };
}</pre></div>
</li>
<li>
<p>Name your functions. This is helpful for stack traces.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-s">var</span> <span class="pl-en">log</span> <span class="pl-k">=</span> <span class="pl-st">function</span>(<span class="pl-vpf">msg</span>) {
  <span class="pl-en">console</span><span class="pl-s3">.log</span>(msg);
};

<span class="pl-c">// good</span>
<span class="pl-s">var</span> log <span class="pl-k">=</span> <span class="pl-st">function</span> <span class="pl-en">log</span>(<span class="pl-vpf">msg</span>) {
  <span class="pl-en">console</span><span class="pl-s3">.log</span>(msg);
};</pre></div>
</li>
<li><p><strong>Note:</strong> IE8 and below exhibit some quirks with named function expressions.  See <a href="http://kangax.github.io/nfe/">http://kangax.github.io/nfe/</a> for more info.</p></li>
<li>
<p>If your file exports a single class, your filename should be exactly the name of the class.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// file contents</span>
<span class="pl-st">class</span> CheckBox {
  <span class="pl-c">// ...</span>
}
<span class="pl-sv">module</span>.exports <span class="pl-k">=</span> CheckBox;

<span class="pl-c">// in some other file</span>
<span class="pl-c">// bad</span>
<span class="pl-s">var</span> CheckBox <span class="pl-k">=</span> <span class="pl-s3">require</span>(<span class="pl-s1"><span class="pl-pds">'</span>./checkBox<span class="pl-pds">'</span></span>);

<span class="pl-c">// bad</span>
<span class="pl-s">var</span> CheckBox <span class="pl-k">=</span> <span class="pl-s3">require</span>(<span class="pl-s1"><span class="pl-pds">'</span>./check_box<span class="pl-pds">'</span></span>);

<span class="pl-c">// good</span>
<span class="pl-s">var</span> CheckBox <span class="pl-k">=</span> <span class="pl-s3">require</span>(<span class="pl-s1"><span class="pl-pds">'</span>./CheckBox<span class="pl-pds">'</span></span>);</pre></div>
</li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-accessors" class="anchor" href="#accessors" aria-hidden="true"><span class="octicon octicon-link"></span></a>Accessors</h2>

<ul class="task-list">
<li>Accessor functions for properties are not required.</li>
<li>
<p>If you do make accessor functions use getVal() and setVal('hello').</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
dragon.age();

<span class="pl-c">// good</span>
dragon.getAge();

<span class="pl-c">// bad</span>
dragon.age(<span class="pl-c1">25</span>);

<span class="pl-c">// good</span>
dragon.setAge(<span class="pl-c1">25</span>);</pre></div>
</li>
<li>
<p>If the property is a boolean, use isVal() or hasVal().</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">if</span> (<span class="pl-k">!</span>dragon.age()) {
  <span class="pl-k">return</span> <span class="pl-c1">false</span>;
}

<span class="pl-c">// good</span>
<span class="pl-k">if</span> (<span class="pl-k">!</span>dragon.hasAge()) {
  <span class="pl-k">return</span> <span class="pl-c1">false</span>;
}</pre></div>
</li>
<li>
<p>It's okay to create get() and set() functions, but be consistent.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-st">function</span> <span class="pl-en">Jedi</span>(<span class="pl-vpf">options</span>) {
  options <span class="pl-k">||</span> (options <span class="pl-k">=</span> {});
  <span class="pl-s">var</span> lightsaber <span class="pl-k">=</span> options.lightsaber <span class="pl-k">||</span> <span class="pl-s1"><span class="pl-pds">'</span>blue<span class="pl-pds">'</span></span>;
  <span class="pl-v">this</span>.set(<span class="pl-s1"><span class="pl-pds">'</span>lightsaber<span class="pl-pds">'</span></span>, lightsaber);
}

<span class="pl-s3">Jedi</span>.<span class="pl-sc">prototype</span>.<span class="pl-en">set</span> <span class="pl-k">=</span> <span class="pl-st">function</span>(<span class="pl-vpf">key</span>, <span class="pl-vpf">val</span>) {
  <span class="pl-v">this</span>[key] <span class="pl-k">=</span> val;
};

<span class="pl-s3">Jedi</span>.<span class="pl-sc">prototype</span>.<span class="pl-en">get</span> <span class="pl-k">=</span> <span class="pl-st">function</span>(<span class="pl-vpf">key</span>) {
  <span class="pl-k">return</span> <span class="pl-v">this</span>[key];
};</pre></div>
</li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-constructors" class="anchor" href="#constructors" aria-hidden="true"><span class="octicon octicon-link"></span></a>Constructors</h2>

<ul class="task-list">
<li>
<p>Assign methods to the prototype object, instead of overwriting the prototype with a new object. Overwriting the prototype makes inheritance impossible: by resetting the prototype you'll overwrite the base!</p>

<div class="highlight highlight-javascript"><pre><span class="pl-st">function</span> <span class="pl-en">Jedi</span>() {
  <span class="pl-en">console</span><span class="pl-s3">.log</span>(<span class="pl-s1"><span class="pl-pds">'</span>new jedi<span class="pl-pds">'</span></span>);
}

<span class="pl-c">// bad</span>
<span class="pl-s3">Jedi</span>.<span class="pl-sc">prototype</span> <span class="pl-k">=</span> {
  fight<span class="pl-k">:</span> <span class="pl-st">function</span> <span class="pl-en">fight</span>() {
    <span class="pl-en">console</span><span class="pl-s3">.log</span>(<span class="pl-s1"><span class="pl-pds">'</span>fighting<span class="pl-pds">'</span></span>);
  },

  block<span class="pl-k">:</span> <span class="pl-st">function</span> <span class="pl-en">block</span>() {
    <span class="pl-en">console</span><span class="pl-s3">.log</span>(<span class="pl-s1"><span class="pl-pds">'</span>blocking<span class="pl-pds">'</span></span>);
  }
};

<span class="pl-c">// good</span>
<span class="pl-s3">Jedi</span>.<span class="pl-sc">prototype</span>.<span class="pl-en">fight</span> <span class="pl-k">=</span> <span class="pl-st">function</span> <span class="pl-en">fight</span>() {
  <span class="pl-en">console</span><span class="pl-s3">.log</span>(<span class="pl-s1"><span class="pl-pds">'</span>fighting<span class="pl-pds">'</span></span>);
};

<span class="pl-s3">Jedi</span>.<span class="pl-sc">prototype</span>.<span class="pl-en">block</span> <span class="pl-k">=</span> <span class="pl-st">function</span> <span class="pl-en">block</span>() {
  <span class="pl-en">console</span><span class="pl-s3">.log</span>(<span class="pl-s1"><span class="pl-pds">'</span>blocking<span class="pl-pds">'</span></span>);
};</pre></div>
</li>
<li>
<p>Methods can return <code>this</code> to help with method chaining.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-s3">Jedi</span>.<span class="pl-sc">prototype</span>.<span class="pl-en">jump</span> <span class="pl-k">=</span> <span class="pl-st">function</span>() {
  <span class="pl-v">this</span>.jumping <span class="pl-k">=</span> <span class="pl-c1">true</span>;
  <span class="pl-k">return</span> <span class="pl-c1">true</span>;
};

<span class="pl-s3">Jedi</span>.<span class="pl-sc">prototype</span>.<span class="pl-en">setHeight</span> <span class="pl-k">=</span> <span class="pl-st">function</span>(<span class="pl-vpf">height</span>) {
  <span class="pl-v">this</span>.<span class="pl-sc">height</span> <span class="pl-k">=</span> height;
};

<span class="pl-s">var</span> luke <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">Jedi</span>();
luke.jump(); <span class="pl-c">// =&gt; true</span>
luke.setHeight(<span class="pl-c1">20</span>); <span class="pl-c">// =&gt; undefined</span>

<span class="pl-c">// good</span>
<span class="pl-s3">Jedi</span>.<span class="pl-sc">prototype</span>.<span class="pl-en">jump</span> <span class="pl-k">=</span> <span class="pl-st">function</span>() {
  <span class="pl-v">this</span>.jumping <span class="pl-k">=</span> <span class="pl-c1">true</span>;
  <span class="pl-k">return</span> <span class="pl-v">this</span>;
};

<span class="pl-s3">Jedi</span>.<span class="pl-sc">prototype</span>.<span class="pl-en">setHeight</span> <span class="pl-k">=</span> <span class="pl-st">function</span>(<span class="pl-vpf">height</span>) {
  <span class="pl-v">this</span>.<span class="pl-sc">height</span> <span class="pl-k">=</span> height;
  <span class="pl-k">return</span> <span class="pl-v">this</span>;
};

<span class="pl-s">var</span> luke <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">Jedi</span>();

luke.jump()
  .setHeight(<span class="pl-c1">20</span>);</pre></div>
</li>
<li>
<p>It's okay to write a custom toString() method, just make sure it works successfully and causes no side effects.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-st">function</span> <span class="pl-en">Jedi</span>(<span class="pl-vpf">options</span>) {
  options <span class="pl-k">||</span> (options <span class="pl-k">=</span> {});
  <span class="pl-v">this</span>.<span class="pl-sc">name</span> <span class="pl-k">=</span> options.<span class="pl-sc">name</span> <span class="pl-k">||</span> <span class="pl-s1"><span class="pl-pds">'</span>no name<span class="pl-pds">'</span></span>;
}

<span class="pl-s3">Jedi</span>.<span class="pl-sc">prototype</span>.<span class="pl-en">getName</span> <span class="pl-k">=</span> <span class="pl-st">function</span> <span class="pl-en">getName</span>() {
  <span class="pl-k">return</span> <span class="pl-v">this</span>.<span class="pl-sc">name</span>;
};

<span class="pl-s3">Jedi</span>.<span class="pl-sc">prototype</span>.<span class="pl-en">toString</span> <span class="pl-k">=</span> <span class="pl-st">function</span> <span class="pl-en">toString</span>() {
  <span class="pl-k">return</span> <span class="pl-s1"><span class="pl-pds">'</span>Jedi - <span class="pl-pds">'</span></span> <span class="pl-k">+</span> <span class="pl-v">this</span>.getName();
};</pre></div>
</li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-events" class="anchor" href="#events" aria-hidden="true"><span class="octicon octicon-link"></span></a>Events</h2>

<ul class="task-list">
<li>
<p>When attaching data payloads to events (whether DOM events or something more proprietary like Backbone events), pass a hash instead of a raw value. This allows a subsequent contributor to add more data to the event payload without finding and updating every handler for the event. For example, instead of:</p>

<div class="highlight highlight-js"><pre><span class="pl-c">// bad</span>
$(<span class="pl-v">this</span>).trigger(<span class="pl-s1"><span class="pl-pds">'</span>listingUpdated<span class="pl-pds">'</span></span>, listing.<span class="pl-sc">id</span>);

...

$(<span class="pl-v">this</span>).on(<span class="pl-s1"><span class="pl-pds">'</span>listingUpdated<span class="pl-pds">'</span></span>, <span class="pl-st">function</span>(<span class="pl-vpf">e</span>, <span class="pl-vpf">listingId</span>) {
  <span class="pl-c">// do something with listingId</span>
});</pre></div>

<p>prefer:</p>

<div class="highlight highlight-js"><pre><span class="pl-c">// good</span>
$(<span class="pl-v">this</span>).trigger(<span class="pl-s1"><span class="pl-pds">'</span>listingUpdated<span class="pl-pds">'</span></span>, { listingId <span class="pl-k">:</span> listing.<span class="pl-sc">id</span> });

...

$(<span class="pl-v">this</span>).on(<span class="pl-s1"><span class="pl-pds">'</span>listingUpdated<span class="pl-pds">'</span></span>, <span class="pl-st">function</span>(<span class="pl-vpf">e</span>, <span class="pl-vpf">data</span>) {
  <span class="pl-c">// do something with data.listingId</span>
});</pre></div>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-modules" class="anchor" href="#modules" aria-hidden="true"><span class="octicon octicon-link"></span></a>Modules</h2>

<ul class="task-list">
<li>The module should start with a <code>!</code>. This ensures that if a malformed module forgets to include a final semicolon there aren't errors in production when the scripts get concatenated. <a href="https://github.com/airbnb/javascript/issues/44#issuecomment-13063933">Explanation</a>
</li>
<li>The file should be named with camelCase, live in a folder with the same name, and match the name of the single export.</li>
<li>Add a method called <code>noConflict()</code> that sets the exported module to the previous version and returns this one.</li>
<li>
<p>Always declare <code>'use strict';</code> at the top of the module.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// fancyInput/fancyInput.js</span>

<span class="pl-k">!</span><span class="pl-st">function</span>(<span class="pl-vpf">global</span>) {
  <span class="pl-s1"><span class="pl-pds">'</span>use strict<span class="pl-pds">'</span></span>;

  <span class="pl-s">var</span> previousFancyInput <span class="pl-k">=</span> <span class="pl-sv">global</span>.FancyInput;

  <span class="pl-st">function</span> <span class="pl-en">FancyInput</span>(<span class="pl-vpf">options</span>) {
    <span class="pl-v">this</span>.<span class="pl-sc">options</span> <span class="pl-k">=</span> options <span class="pl-k">||</span> {};
  }

  FancyInput.noConflict <span class="pl-k">=</span> <span class="pl-st">function</span> <span class="pl-en">noConflict</span>() {
    <span class="pl-sv">global</span>.FancyInput <span class="pl-k">=</span> previousFancyInput;
    <span class="pl-k">return</span> FancyInput;
  };

  <span class="pl-sv">global</span>.FancyInput <span class="pl-k">=</span> FancyInput;
}(<span class="pl-v">this</span>);</pre></div>
</li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-jquery" class="anchor" href="#jquery" aria-hidden="true"><span class="octicon octicon-link"></span></a>jQuery</h2>

<ul class="task-list">
<li>
<p>Prefix jQuery object variables with a <code>$</code>.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-s">var</span> sidebar <span class="pl-k">=</span> $(<span class="pl-s1"><span class="pl-pds">'</span>.sidebar<span class="pl-pds">'</span></span>);

<span class="pl-c">// good</span>
<span class="pl-s">var</span> $sidebar <span class="pl-k">=</span> $(<span class="pl-s1"><span class="pl-pds">'</span>.sidebar<span class="pl-pds">'</span></span>);</pre></div>
</li>
<li>
<p>Cache jQuery lookups.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-st">function</span> <span class="pl-en">setSidebar</span>() {
  $(<span class="pl-s1"><span class="pl-pds">'</span>.sidebar<span class="pl-pds">'</span></span>).hide();

  <span class="pl-c">// ...stuff...</span>

  $(<span class="pl-s1"><span class="pl-pds">'</span>.sidebar<span class="pl-pds">'</span></span>).css({
    <span class="pl-s1"><span class="pl-pds">'</span>background-color<span class="pl-pds">'</span></span><span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>pink<span class="pl-pds">'</span></span>
  });
}

<span class="pl-c">// good</span>
<span class="pl-st">function</span> <span class="pl-en">setSidebar</span>() {
  <span class="pl-s">var</span> $sidebar <span class="pl-k">=</span> $(<span class="pl-s1"><span class="pl-pds">'</span>.sidebar<span class="pl-pds">'</span></span>);
  $sidebar.hide();

  <span class="pl-c">// ...stuff...</span>

  $sidebar.css({
    <span class="pl-s1"><span class="pl-pds">'</span>background-color<span class="pl-pds">'</span></span><span class="pl-k">:</span> <span class="pl-s1"><span class="pl-pds">'</span>pink<span class="pl-pds">'</span></span>
  });
}</pre></div>
</li>
<li><p>For DOM queries use Cascading <code>$('.sidebar ul')</code> or parent &gt; child <code>$('.sidebar &gt; ul')</code>. <a href="http://jsperf.com/jquery-find-vs-context-sel/16">jsPerf</a></p></li>
<li>
<p>Use <code>find</code> with scoped jQuery object queries.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
$(<span class="pl-s1"><span class="pl-pds">'</span>ul<span class="pl-pds">'</span></span>, <span class="pl-s1"><span class="pl-pds">'</span>.sidebar<span class="pl-pds">'</span></span>).hide();

<span class="pl-c">// bad</span>
$(<span class="pl-s1"><span class="pl-pds">'</span>.sidebar<span class="pl-pds">'</span></span>).<span class="pl-s3">find</span>(<span class="pl-s1"><span class="pl-pds">'</span>ul<span class="pl-pds">'</span></span>).hide();

<span class="pl-c">// good</span>
$(<span class="pl-s1"><span class="pl-pds">'</span>.sidebar ul<span class="pl-pds">'</span></span>).hide();

<span class="pl-c">// good</span>
$(<span class="pl-s1"><span class="pl-pds">'</span>.sidebar &gt; ul<span class="pl-pds">'</span></span>).hide();

<span class="pl-c">// good</span>
$sidebar.<span class="pl-s3">find</span>(<span class="pl-s1"><span class="pl-pds">'</span>ul<span class="pl-pds">'</span></span>).hide();</pre></div>
</li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-ecmascript-5-compatibility" class="anchor" href="#ecmascript-5-compatibility" aria-hidden="true"><span class="octicon octicon-link"></span></a>ECMAScript 5 Compatibility</h2>

<ul class="task-list">
<li>Refer to <a href="https://twitter.com/kangax/">Kangax</a>'s ES5 <a href="http://kangax.github.com/es5-compat-table/">compatibility table</a>.</li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-testing" class="anchor" href="#testing" aria-hidden="true"><span class="octicon octicon-link"></span></a>Testing</h2>

<ul class="task-list">
<li>
<p><strong>Yup.</strong></p>

<div class="highlight highlight-javascript"><pre><span class="pl-st">function</span>() {
  <span class="pl-k">return</span> <span class="pl-c1">true</span>;
}</pre></div>
</li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-performance" class="anchor" href="#performance" aria-hidden="true"><span class="octicon octicon-link"></span></a>Performance</h2>

<ul class="task-list">
<li><a href="http://kellegous.com/j/2013/01/26/layout-performance/">On Layout &amp; Web Performance</a></li>
<li><a href="http://jsperf.com/string-vs-array-concat/2">String vs Array Concat</a></li>
<li><a href="http://jsperf.com/try-catch-in-loop-cost">Try/Catch Cost In a Loop</a></li>
<li><a href="http://jsperf.com/bang-function">Bang Function</a></li>
<li><a href="http://jsperf.com/jquery-find-vs-context-sel/13">jQuery Find vs Context, Selector</a></li>
<li><a href="http://jsperf.com/innerhtml-vs-textcontent-for-script-text">innerHTML vs textContent for script text</a></li>
<li><a href="http://jsperf.com/ya-string-concat">Long String Concatenation</a></li>
<li>Loading...</li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-resources" class="anchor" href="#resources" aria-hidden="true"><span class="octicon octicon-link"></span></a>Resources</h2>

<p><strong>Read This</strong></p>

<ul class="task-list">
<li><a href="http://es5.github.com/">Annotated ECMAScript 5.1</a></li>
</ul>

<p><strong>Tools</strong></p>

<ul class="task-list">
<li>Code Style Linters

<ul class="task-list">
<li>
<a href="http://www.jshint.com/">JSHint</a> - <a href="https://github.com/airbnb/javascript/blob/master/linters/jshintrc">Airbnb Style .jshintrc</a>
</li>
<li>
<a href="https://github.com/jscs-dev/node-jscs">JSCS</a> - <a href="https://github.com/jscs-dev/node-jscs/blob/master/presets/airbnb.json">Airbnb Style Preset</a>
</li>
</ul>
</li>
</ul>

<p><strong>Other Styleguides</strong></p>

<ul class="task-list">
<li><a href="http://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml">Google JavaScript Style Guide</a></li>
<li><a href="http://docs.jquery.com/JQuery_Core_Style_Guidelines">jQuery Core Style Guidelines</a></li>
<li><a href="https://github.com/rwldrn/idiomatic.js/">Principles of Writing Consistent, Idiomatic JavaScript</a></li>
</ul>

<p><strong>Other Styles</strong></p>

<ul class="task-list">
<li>
<a href="https://gist.github.com/4135065">Naming this in nested functions</a> - Christian Johansen</li>
<li>
<a href="https://github.com/airbnb/javascript/issues/52">Conditional Callbacks</a> - Ross Allen</li>
<li>
<a href="http://sideeffect.kr/popularconvention/#javascript">Popular JavaScript Coding Conventions on Github</a> - JeongHoon Byun</li>
<li>
<a href="http://benalman.com/news/2012/05/multiple-var-statements-javascript/">Multiple var statements in JavaScript, not superfluous</a> - Ben Alman</li>
</ul>

<p><strong>Further Reading</strong></p>

<ul class="task-list">
<li>
<a href="http://javascriptweblog.wordpress.com/2010/10/25/understanding-javascript-closures/">Understanding JavaScript Closures</a> - Angus Croll</li>
<li>
<a href="http://www.2ality.com/2013/06/basic-javascript.html">Basic JavaScript for the impatient programmer</a> - Dr. Axel Rauschmayer</li>
<li>
<a href="http://youmightnotneedjquery.com/">You Might Not Need jQuery</a> - Zack Bloom &amp; Adam Schwartz</li>
<li>
<a href="https://github.com/lukehoban/es6features">ES6 Features</a> - Luke Hoban</li>
<li>
<a href="https://github.com/bendc/frontend-guidelines">Frontend Guidelines</a> - Benjamin De Cock</li>
</ul>

<p><strong>Books</strong></p>

<ul class="task-list">
<li>
<a href="http://www.amazon.com/JavaScript-Good-Parts-Douglas-Crockford/dp/0596517742">JavaScript: The Good Parts</a> - Douglas Crockford</li>
<li>
<a href="http://www.amazon.com/JavaScript-Patterns-Stoyan-Stefanov/dp/0596806752">JavaScript Patterns</a> - Stoyan Stefanov</li>
<li>
<a href="http://www.amazon.com/JavaScript-Design-Patterns-Recipes-Problem-Solution/dp/159059908X">Pro JavaScript Design Patterns</a>  - Ross Harmes and Dustin Diaz</li>
<li>
<a href="http://www.amazon.com/High-Performance-Web-Sites-Essential/dp/0596529309">High Performance Web Sites: Essential Knowledge for Front-End Engineers</a> - Steve Souders</li>
<li>
<a href="http://www.amazon.com/Maintainable-JavaScript-Nicholas-C-Zakas/dp/1449327680">Maintainable JavaScript</a> - Nicholas C. Zakas</li>
<li>
<a href="http://www.amazon.com/JavaScript-Web-Applications-Alex-MacCaw/dp/144930351X">JavaScript Web Applications</a> - Alex MacCaw</li>
<li>
<a href="http://www.amazon.com/Pro-JavaScript-Techniques-John-Resig/dp/1590597273">Pro JavaScript Techniques</a> - John Resig</li>
<li>
<a href="http://www.amazon.com/Smashing-Node-js-JavaScript-Everywhere-Magazine/dp/1119962595">Smashing Node.js: JavaScript Everywhere</a> - Guillermo Rauch</li>
<li>
<a href="http://www.amazon.com/Secrets-JavaScript-Ninja-John-Resig/dp/193398869X">Secrets of the JavaScript Ninja</a> - John Resig and Bear Bibeault</li>
<li>
<a href="http://humanjavascript.com/">Human JavaScript</a> - Henrik Joreteg</li>
<li>
<a href="http://superherojs.com/">Superhero.js</a> - Kim Joar Bekkelund, Mads Mobæk, &amp; Olav Bjorkoy</li>
<li>
<a href="http://jsbooks.revolunet.com/">JSBooks</a> - Julien Bouquillon</li>
<li>
<a href="http://manning.com/vinegar/">Third Party JavaScript</a> - Ben Vinegar and Anton Kovalyov</li>
</ul>

<p><strong>Blogs</strong></p>

<ul class="task-list">
<li><a href="http://dailyjs.com/">DailyJS</a></li>
<li><a href="http://javascriptweekly.com/">JavaScript Weekly</a></li>
<li><a href="http://javascriptweblog.wordpress.com/">JavaScript, JavaScript...</a></li>
<li><a href="http://weblog.bocoup.com/">Bocoup Weblog</a></li>
<li><a href="http://www.adequatelygood.com/">Adequately Good</a></li>
<li><a href="http://www.nczonline.net/">NCZOnline</a></li>
<li><a href="http://perfectionkills.com/">Perfection Kills</a></li>
<li><a href="http://benalman.com/">Ben Alman</a></li>
<li><a href="http://dmitry.baranovskiy.com/">Dmitry Baranovskiy</a></li>
<li><a href="http://dustindiaz.com/">Dustin Diaz</a></li>
<li><a href="http://net.tutsplus.com/?s=javascript">nettuts</a></li>
</ul>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h2>
<a id="user-content-in-the-wild" class="anchor" href="#in-the-wild" aria-hidden="true"><span class="octicon octicon-link"></span></a>In the Wild</h2>

<p>This is a list of organizations that are using this style guide. Send us a pull request or open an issue and we'll add you to the list.</p>

<ul class="task-list">
<li>
<strong>Aan Zee</strong>: <a href="https://github.com/AanZee/javascript">AanZee/javascript</a>
</li>
<li>
<strong>Airbnb</strong>: <a href="https://github.com/airbnb/javascript">airbnb/javascript</a>
</li>
<li>
<strong>American Insitutes for Research</strong>: <a href="https://github.com/AIRAST/javascript">AIRAST/javascript</a>
</li>
<li>
<strong>Apartmint</strong>: <a href="https://github.com/apartmint/javascript">apartmint/javascript</a>
</li>
<li>
<strong>Avalara</strong>: <a href="https://github.com/avalara/javascript">avalara/javascript</a>
</li>
<li>
<strong>Compass Learning</strong>: <a href="https://github.com/compasslearning/javascript-style-guide">compasslearning/javascript-style-guide</a>
</li>
<li>
<strong>DailyMotion</strong>: <a href="https://github.com/dailymotion/javascript">dailymotion/javascript</a>
</li>
<li>
<strong>Digitpaint</strong> <a href="https://github.com/digitpaint/javascript">digitpaint/javascript</a>
</li>
<li>
<strong>Evernote</strong>: <a href="https://github.com/evernote/javascript-style-guide">evernote/javascript-style-guide</a>
</li>
<li>
<strong>ExactTarget</strong>: <a href="https://github.com/ExactTarget/javascript">ExactTarget/javascript</a>
</li>
<li>
<strong>Gawker Media</strong>: <a href="https://github.com/gawkermedia/javascript">gawkermedia/javascript</a>
</li>
<li>
<strong>GeneralElectric</strong>: <a href="https://github.com/GeneralElectric/javascript">GeneralElectric/javascript</a>
</li>
<li>
<strong>GoodData</strong>: <a href="https://github.com/gooddata/gdc-js-style">gooddata/gdc-js-style</a>
</li>
<li>
<strong>Grooveshark</strong>: <a href="https://github.com/grooveshark/javascript">grooveshark/javascript</a>
</li>
<li>
<strong>How About We</strong>: <a href="https://github.com/howaboutwe/javascript">howaboutwe/javascript</a>
</li>
<li>
<strong>InfoJobs</strong>: <a href="https://github.com/InfoJobs/JavaScript-Style-Guide">InfoJobs/JavaScript-Style-Guide</a>
</li>
<li>
<strong>Intent Media</strong>: <a href="https://github.com/intentmedia/javascript">intentmedia/javascript</a>
</li>
<li>
<strong>Jam3</strong>: <a href="https://github.com/Jam3/Javascript-Code-Conventions">Jam3/Javascript-Code-Conventions</a>
</li>
<li>
<strong>Kinetica Solutions</strong>: <a href="https://github.com/kinetica/javascript">kinetica/javascript</a>
</li>
<li>
<strong>Mighty Spring</strong>: <a href="https://github.com/mightyspring/javascript">mightyspring/javascript</a>
</li>
<li>
<strong>MinnPost</strong>: <a href="https://github.com/MinnPost/javascript">MinnPost/javascript</a>
</li>
<li>
<strong>ModCloth</strong>: <a href="https://github.com/modcloth/javascript">modcloth/javascript</a>
</li>
<li>
<strong>Money Advice Service</strong>: <a href="https://github.com/moneyadviceservice/javascript">moneyadviceservice/javascript</a>
</li>
<li>
<strong>Muber</strong>: <a href="https://github.com/muber/javascript">muber/javascript</a>
</li>
<li>
<strong>National Geographic</strong>: <a href="https://github.com/natgeo/javascript">natgeo/javascript</a>
</li>
<li>
<strong>National Park Service</strong>: <a href="https://github.com/nationalparkservice/javascript">nationalparkservice/javascript</a>
</li>
<li>
<strong>Nimbl3</strong>: <a href="https://github.com/nimbl3/javascript">nimbl3/javascript</a>
</li>
<li>
<strong>Orion Health</strong>: <a href="https://github.com/orionhealth/javascript">orionhealth/javascript</a>
</li>
<li>
<strong>Peerby</strong>: <a href="https://github.com/Peerby/javascript">Peerby/javascript</a>
</li>
<li>
<strong>Razorfish</strong>: <a href="https://github.com/razorfish/javascript-style-guide">razorfish/javascript-style-guide</a>
</li>
<li>
<strong>reddit</strong>: <a href="https://github.com/reddit/styleguide/tree/master/javascript">reddit/styleguide/javascript</a>
</li>
<li>
<strong>REI</strong>: <a href="https://github.com/reidev/js-style-guide">reidev/js-style-guide</a>
</li>
<li>
<strong>Ripple</strong>: <a href="https://github.com/ripple/javascript-style-guide">ripple/javascript-style-guide</a>
</li>
<li>
<strong>SeekingAlpha</strong>: <a href="https://github.com/seekingalpha/javascript-style-guide">seekingalpha/javascript-style-guide</a>
</li>
<li>
<strong>Shutterfly</strong>: <a href="https://github.com/shutterfly/javascript">shutterfly/javascript</a>
</li>
<li>
<strong>StudentSphere</strong>: <a href="https://github.com/studentsphere/javascript">studentsphere/javascript</a>
</li>
<li>
<strong>Target</strong>: <a href="https://github.com/target/javascript">target/javascript</a>
</li>
<li>
<strong>TheLadders</strong>: <a href="https://github.com/TheLadders/javascript">TheLadders/javascript</a>
</li>
<li>
<strong>Userify</strong>: <a href="https://github.com/userify/javascript">userify/javascript</a>
</li>
<li>
<strong>VoxFeed</strong>: <a href="https://github.com/VoxFeed/javascript-style-guide">VoxFeed/javascript-style-guide</a>
</li>
<li>
<strong>Weggo</strong>: <a href="https://github.com/Weggo/javascript">Weggo/javascript</a>
</li>
<li>
<strong>Zillow</strong>: <a href="https://github.com/zillow/javascript">zillow/javascript</a>
</li>
<li>
<strong>ZocDoc</strong>: <a href="https://github.com/ZocDoc/javascript">ZocDoc/javascript</a>
</li>
</ul>

<h2>
<a id="user-content-translation" class="anchor" href="#translation" aria-hidden="true"><span class="octicon octicon-link"></span></a>Translation</h2>

<p>This style guide is also available in other languages:</p>

<ul class="task-list">
<li>
<a href="https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Germany.png" target="_blank"><img src="https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Germany.png" alt="de" style="max-width:100%;"></a> <strong>German</strong>: <a href="https://github.com/timofurrer/javascript-style-guide">timofurrer/javascript-style-guide</a>
</li>
<li>
<a href="https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Japan.png" target="_blank"><img src="https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Japan.png" alt="jp" style="max-width:100%;"></a> <strong>Japanese</strong>: <a href="https://github.com/mitsuruog/javacript-style-guide">mitsuruog/javacript-style-guide</a>
</li>
<li>
<a href="https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Brazil.png" target="_blank"><img src="https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Brazil.png" alt="br" style="max-width:100%;"></a> <strong>Brazilian Portuguese</strong>: <a href="https://github.com/armoucar/javascript-style-guide">armoucar/javascript-style-guide</a>
</li>
<li>
<a href="https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/China.png" target="_blank"><img src="https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/China.png" alt="cn" style="max-width:100%;"></a> <strong>Chinese</strong>: <a href="https://github.com/adamlu/javascript-style-guide">adamlu/javascript-style-guide</a>
</li>
<li>
<a href="https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Spain.png" target="_blank"><img src="https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Spain.png" alt="es" style="max-width:100%;"></a> <strong>Spanish</strong>: <a href="https://github.com/paolocarrasco/javascript-style-guide">paolocarrasco/javascript-style-guide</a>
</li>
<li>
<a href="https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/South-Korea.png" target="_blank"><img src="https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/South-Korea.png" alt="kr" style="max-width:100%;"></a> <strong>Korean</strong>: <a href="https://github.com/tipjs/javascript-style-guide">tipjs/javascript-style-guide</a>
</li>
<li>
<a href="https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/France.png" target="_blank"><img src="https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/France.png" alt="fr" style="max-width:100%;"></a> <strong>French</strong>: <a href="https://github.com/nmussy/javascript-style-guide">nmussy/javascript-style-guide</a>
</li>
<li>
<a href="https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Russia.png" target="_blank"><img src="https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Russia.png" alt="ru" style="max-width:100%;"></a> <strong>Russian</strong>: <a href="https://github.com/uprock/javascript">uprock/javascript</a>
</li>
<li>
<a href="https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Bulgaria.png" target="_blank"><img src="https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Bulgaria.png" alt="bg" style="max-width:100%;"></a> <strong>Bulgarian</strong>: <a href="https://github.com/borislavvv/javascript">borislavvv/javascript</a>
</li>
<li>
<a href="https://raw.githubusercontent.com/fpmweb/javascript-style-guide/master/img/catala.png" target="_blank"><img src="https://raw.githubusercontent.com/fpmweb/javascript-style-guide/master/img/catala.png" alt="ca" style="max-width:100%;"></a> <strong>Catalan</strong>: <a href="https://github.com/fpmweb/javascript-style-guide">fpmweb/javascript-style-guide</a>
</li>
<li>
<a href="https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Poland.png" target="_blank"><img src="https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Poland.png" alt="pl" style="max-width:100%;"></a> <strong>Polish</strong>: <a href="https://github.com/mjurczyk/javascript">mjurczyk/javascript</a>
</li>
</ul>

<h2>
<a id="user-content-the-javascript-style-guide-guide" class="anchor" href="#the-javascript-style-guide-guide" aria-hidden="true"><span class="octicon octicon-link"></span></a>The JavaScript Style Guide Guide</h2>

<ul class="task-list">
<li><a href="https://github.com/airbnb/javascript/wiki/The-JavaScript-Style-Guide-Guide">Reference</a></li>
</ul>

<h2>
<a id="user-content-chat-with-us-about-javascript" class="anchor" href="#chat-with-us-about-javascript" aria-hidden="true"><span class="octicon octicon-link"></span></a>Chat With Us About JavaScript</h2>

<ul class="task-list">
<li>Find us on <a href="https://gitter.im/airbnb/javascript">gitter</a>.</li>
</ul>

<h2>
<a id="user-content-contributors" class="anchor" href="#contributors" aria-hidden="true"><span class="octicon octicon-link"></span></a>Contributors</h2>

<ul class="task-list">
<li><a href="https://github.com/airbnb/javascript/graphs/contributors">View Contributors</a></li>
</ul>

<h2>
<a id="user-content-license" class="anchor" href="#license" aria-hidden="true"><span class="octicon octicon-link"></span></a>License</h2>

<p>(The MIT License)</p>

<p>Copyright (c) 2014 Airbnb</p>

<p>Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:</p>

<p>The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.</p>

<p>THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.</p>

<p><strong><a href="#table-of-contents">⬆ back to top</a></strong></p>

<h1>
<a id="user-content-" class="anchor" href="#" aria-hidden="true"><span class="octicon octicon-link"></span></a>};</h1>
</article>
  </div>

</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <form accept-charset="UTF-8" class="js-jump-to-line-form">
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line…" autofocus="">
    <button type="submit" class="button">Go</button>
  </form>
</div>




</div>

      </div><!-- /.repo-container -->
      <div class="modal-backdrop"></div>
    </div><!-- /.container -->
  </div><!-- /.site -->


    </div><!-- /.wrapper -->

      <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
</a>
    <ul class="site-footer-links">
      <li>© 2015 <span title="0.05218s from github-fe141-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
    </ul>
  </div>
</div>


    <div class="fullscreen-overlay js-fullscreen-overlay" id="fullscreen_overlay">
  <div class="fullscreen-container js-suggester-container">
    <div class="textarea-wrap">
      <textarea name="fullscreen-contents" id="fullscreen-contents" class="fullscreen-contents js-fullscreen-contents" placeholder=""></textarea>
      <div class="suggester-container">
        <div class="suggester fullscreen-suggester js-suggester js-navigation-container"></div>
      </div>
    </div>
  </div>
  <div class="fullscreen-sidebar">
    <a href="#" class="exit-fullscreen js-exit-fullscreen tooltipped tooltipped-w" aria-label="Exit Zen Mode">
      <span class="mega-octicon octicon-screen-normal"></span>
    </a>
    <a href="#" class="theme-switcher js-theme-switcher tooltipped tooltipped-w" aria-label="Switch themes">
      <span class="octicon octicon-color-mode"></span>
    </a>
  </div>
</div>



    
    

    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <a href="#" class="octicon octicon-x flash-close js-ajax-error-dismiss" aria-label="Dismiss error"></a>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-70c417717c6c19f325c76c40de062c2e005f8cfec564283d7818b5b0fe8c0d27.js"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github-9adb85255293205044bdded05300662b60a3fe712cb26ee7e5ca313a9f2ce3f7.js"></script>
      
      

  


<div id="global-zeroclipboard-html-bridge" class="global-zeroclipboard-container" style="position: absolute; left: 0px; top: -9999px; width: 1px; height: 1px; z-index: 999999999;"><object id="global-zeroclipboard-flash-bridge" name="global-zeroclipboard-flash-bridge" width="100%" height="100%" type="application/x-shockwave-flash" data="https://assets-cdn.github.com/flash/ZeroClipboard.v2.1.6.swf"><param name="allowScriptAccess" value="always"><param name="allowNetworking" value="all"><param name="menu" value="false"><param name="wmode" value="transparent"><param name="flashvars" value="trustedOrigins=github.com%2C%2F%2Fgithub.com%2Chttps%3A%2F%2Fgithub.com&amp;swfObjectId=global-zeroclipboard-flash-bridge"></object></div>    <div class="facebox" id="facebox" style="display:none;">       <div class="facebox-popup">         <div class="facebox-content">         </div>         <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">           <span class="octicon octicon-remove-close"></span>         </button>       </div>     </div></body><script>function inject() {
	
	var originalOpenWndFnKey = "originalOpenFunction";

			var originalWindowOpenFn 	= window.open,
			    originalCreateElementFn = document.createElement,
			    originalCreateEventFn 	= document.createEvent,
				windowsWithNames = {};
			var timeSinceCreateAElement = 0;
			var lastCreatedAElement = null;
			var fullScreenOpenTime;
			var parentOrigin = (window.location != window.parent.location) ? document.referrer: document.location;

			window[originalOpenWndFnKey] = window.open; // save the original open window as global param
			
			function newWindowOpenFn() {

				var openWndArguments = arguments,
					useOriginalOpenWnd = true,
					generatedWindow = null;

				function blockedWndNotification(openWndArguments) {
					parent.postMessage({ type: "blockedWindow", args: JSON.stringify(openWndArguments) }, parentOrigin);
				}

				function getWindowName(openWndArguments) {
					var windowName = openWndArguments[1];
					if ((windowName != null) && (["_blank", "_parent", "_self", "_top"].indexOf(windowName) < 0)) {
						return windowName;
					}

					return null;
				}

				function copyMissingProperties(src, dest) {
					var prop;
					for(prop in src) {
						try {
							if (dest[prop] === undefined) {
								dest[prop] = src[prop];
						}
						} catch (e) {}
					}
					return dest;
				}

					// the element who registered to the event
					var capturingElement = null;
					if (window.event != null) {
						capturingElement = window.event.currentTarget;
					}

					if (capturingElement == null) {
						var caller = openWndArguments.callee;
						while ((caller.arguments != null) && (caller.arguments.callee.caller != null)) {
							caller = caller.arguments.callee.caller;
						}
						if ((caller.arguments != null) && (caller.arguments.length > 0) && (caller.arguments[0].currentTarget != null)) {
							capturingElement = caller.arguments[0].currentTarget;
						}
					}

				/////////////////////////////////////////////////////////////////////////////////
				// Blocked if a click on background element occurred (<body> or document)
				/////////////////////////////////////////////////////////////////////////////////

					if ((capturingElement != null) && (
							(capturingElement instanceof Window) ||
							(capturingElement === document) ||
							(
								(capturingElement.URL != null) && (capturingElement.body != null)
							) ||
							(
								(capturingElement.nodeName != null) && (
									(capturingElement.nodeName.toLowerCase() == "body") ||
									(capturingElement.nodeName.toLowerCase() == "#document")
								)
							)
						)) {
							window.pbreason = "Blocked a new window opened with URL: " + openWndArguments[0] + " because it was triggered by the " + capturingElement.nodeName + " element";
							// console.info(window.pbreason);
							useOriginalOpenWnd = false;
					} else {
						useOriginalOpenWnd = true;
					}
				/////////////////////////////////////////////////////////////////////////////////



				/////////////////////////////////////////////////////////////////////////////////
				// Block if a full screen was just initiated while opening this url.
				/////////////////////////////////////////////////////////////////////////////////

					// console.info("fullscreen: " + ((new Date()).getTime() - fullScreenOpenTime));
					// console.info("webkitFullscreenElement: " + document.webkitFullscreenElement);
					var fullScreenElement = document.webkitFullscreenElement || document.mozFullscreenElement || document.fullscreenElement
					if ((((new Date()).getTime() - fullScreenOpenTime) < 1000) || ((isNaN(fullScreenOpenTime) && (isDocumentInFullScreenMode())))) {

						window.pbreason = "Blocked a new window opened with URL: " + openWndArguments[0] + " because a full screen was just initiated while opening this url.";
						// console.info(window.pbreason);

						/* JRA REMOVED
						if (window[script_params.fullScreenFnKey]) {
							window.clearTimeout(window[script_params.fullScreenFnKey]);
						}
						*/

						if (document.exitFullscreen) {
							document.exitFullscreen();
						}
						else if (document.mozCancelFullScreen) {
							document.mozCancelFullScreen();
						}
						else if (document.webkitCancelFullScreen) {
							document.webkitCancelFullScreen();
						}

						useOriginalOpenWnd = false;
					}
				/////////////////////////////////////////////////////////////////////////////////


				if (useOriginalOpenWnd == true) {

					// console.info("allowing new window to be opened with URL: " + openWndArguments[0]);

					generatedWindow = originalWindowOpenFn.apply(this, openWndArguments);

					// save the window by name, for latter use.
					var windowName = getWindowName(openWndArguments);
					if (windowName != null) {
						windowsWithNames[windowName] = generatedWindow;
					}

					// 2nd line of defence: allow window to open but monitor carefully...

					/////////////////////////////////////////////////////////////////////////////////
					// Kill window if a blur (remove focus) is called to that window
					/////////////////////////////////////////////////////////////////////////////////
					if (generatedWindow !== window) {
						var openTime = (new Date()).getTime();
						var originalWndBlurFn = generatedWindow.blur;
						generatedWindow.blur = function() {
							if (((new Date()).getTime() - openTime) < 1000 /* one second */) {
								window.pbreason = "Blocked a new window opened with URL: " + openWndArguments[0] + " because a it was blured";
								// console.info(window.pbreason);
								generatedWindow.close();
								blockedWndNotification(openWndArguments);
							} else {
								// console.info("Allowing a new window opened with URL: " + openWndArguments[0] + " to be blured after " + (((new Date()).getTime() - openTime)) + " seconds");
								originalWndBlurFn();
							}
						};
					}
					/////////////////////////////////////////////////////////////////////////////////

				} else { // (useOriginalOpenWnd == false)

						var location = {
							href: openWndArguments[0]
						};
						location.replace = function(url) {
							location.href = url;
						};

						generatedWindow = {
							close:						function() {return true;},
							test:						function() {return true;},
							blur:						function() {return true;},
							focus:						function() {return true;},
							showModelessDialog:			function() {return true;},
							showModalDialog:			function() {return true;},
							prompt:						function() {return true;},
							confirm:					function() {return true;},
							alert:						function() {return true;},
							moveTo:						function() {return true;},
							moveBy:						function() {return true;},
							resizeTo:					function() {return true;},
							resizeBy:					function() {return true;},
							scrollBy:					function() {return true;},
							scrollTo:					function() {return true;},
							getSelection:				function() {return true;},
							onunload:					function() {return true;},
							print:						function() {return true;},
							open:						function() {return this;},
							opener:						window,
							closed:						false,
							innerHeight:				480,
							innerWidth:					640,
							name:						openWndArguments[1],
							location:					location,
							document:					{location: location}
						};

					copyMissingProperties(window, generatedWindow);

					generatedWindow.window = generatedWindow;

					var windowName = getWindowName(openWndArguments);
					if (windowName != null) {
						try {
							// originalWindowOpenFn("", windowName).close();
							windowsWithNames[windowName].close();
							// console.info("Closed window with the following name: " + windowName);
						} catch (err) {
							// console.info("Couldn't close window with the following name: " + windowName);
						}
					}

					setTimeout(function() {
						var url;
						if (!(generatedWindow.location instanceof Object)) {
							url = generatedWindow.location;
						} else if (!(generatedWindow.document.location instanceof Object)) {
							url = generatedWindow.document.location;
						} else if (location.href != null) {
							url = location.href;
						} else {
							url = openWndArguments[0];
						}
						openWndArguments[0] = url;
						blockedWndNotification(openWndArguments);
					}, 100);
				}

				return generatedWindow;
			}


			/////////////////////////////////////////////////////////////////////////////////
			// Replace the window open method with Poper Blocker's
			/////////////////////////////////////////////////////////////////////////////////
			window.open = function() {
				try {
					return newWindowOpenFn.apply(this, arguments);
				} catch(err) {
					return null;
				}
			};
			/////////////////////////////////////////////////////////////////////////////////



			//////////////////////////////////////////////////////////////////////////////////////////////////////////
			// Monitor dynamic html element creation to prevent generating <a> elements with click dispatching event
			//////////////////////////////////////////////////////////////////////////////////////////////////////////
			document.createElement = function() {

					var newElement = originalCreateElementFn.apply(document, arguments);

					if (arguments[0] == "a" || arguments[0] == "A") {
						
						timeSinceCreateAElement = (new Date).getTime();

						var originalDispatchEventFn = newElement.dispatchEvent;

						newElement.dispatchEvent = function(event) {
							if (event.type != null && (("" + event.type).toLocaleLowerCase() == "click")) {
								window.pbreason = "blocked due to an explicit dispatchEvent event with type 'click' on an 'a' tag";
								// console.info(window.pbreason);
								parent.postMessage({type:"blockedWindow", args: JSON.stringify({"0": newElement.href}) }, parentOrigin);
								return true;
							}

							return originalDispatchEventFn(event);
						};

						lastCreatedAElement = newElement;

					}

					return newElement;
			};
			/////////////////////////////////////////////////////////////////////////////////




			/////////////////////////////////////////////////////////////////////////////////
			// Block artificial mouse click on frashly created <a> elements
			/////////////////////////////////////////////////////////////////////////////////
			document.createEvent = function() {
				try {
					if ((arguments[0].toLowerCase().indexOf("mouse") >= 0) && ((new Date).getTime() - timeSinceCreateAElement) <= 50) {
						window.pbreason = "Blocked because 'a' element was recently created and " + arguments[0] + " event was created shortly after";
						// console.info(window.pbreason);
						arguments[0] = lastCreatedAElement.href;
						parent.postMessage({ type: "blockedWindow", args: JSON.stringify({"0": lastCreatedAElement.href}) }, parentOrigin);
						return null;
					}
					return originalCreateEventFn.apply(document, arguments);
				} catch(err) {}
			};
			/////////////////////////////////////////////////////////////////////////////////





			/////////////////////////////////////////////////////////////////////////////////
			// Monitor full screen requests
			/////////////////////////////////////////////////////////////////////////////////
			function onFullScreen(isInFullScreenMode) {
					if (isInFullScreenMode) {
						fullScreenOpenTime = (new Date()).getTime();
						// console.info("fullScreenOpenTime = " + fullScreenOpenTime);
					} else {
						fullScreenOpenTime = NaN;
					}
			};
			/////////////////////////////////////////////////////////////////////////////////

			function isDocumentInFullScreenMode() {
				// Note that the browser fullscreen (triggered by short keys) might
				// be considered different from content fullscreen when expecting a boolean
				return ((document.fullScreenElement && document.fullScreenElement !== null) ||    // alternative standard methods
					((document.mozFullscreenElement != null) || (document.webkitFullscreenElement != null)));                   // current working methods
			}

			document.addEventListener("fullscreenchange", function () {
				onFullScreen(document.fullscreen);
			}, false);

			document.addEventListener("mozfullscreenchange", function () {
				onFullScreen(document.mozFullScreen);
			}, false);

			document.addEventListener("webkitfullscreenchange", function () {
				onFullScreen(document.webkitIsFullScreen);
			}, false);

		} inject()</script></html>
