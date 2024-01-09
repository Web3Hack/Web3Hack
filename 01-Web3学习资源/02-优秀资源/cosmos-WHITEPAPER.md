





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://assets-cdn.github.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" media="all" integrity="sha512-PkbtxdWDpLChpxtWQ0KbvJoef4XMYPq5pfd/ZmylYZTzXYpCfGwN9d+bsSKcmOJLwTkfjFkfj5wz3poDrhJoSQ==" rel="stylesheet" href="https://assets-cdn.github.com/assets/frameworks-f6e6ce21346c0d2eb22def1e8534afcb.css" />
  <link crossorigin="anonymous" media="all" integrity="sha512-EuadCD9/LFVfed/klpP7kj+qTP0hWhyJ9KN6kLBEXRSLjXEKjm4Z4JORqgppbiE/toxjWa60Fjsh9BtIJdLq9g==" rel="stylesheet" href="https://assets-cdn.github.com/assets/github-6353b64247f8dd959d2b123ae98fba98.css" />
  
  
  <link crossorigin="anonymous" media="all" integrity="sha512-zyxweUSm/NG+juywqcMFSS4HbKjLWCZyEM2JjoCqnQUU6RVrHpHMwH66xreiaeMIRoA6vYuk0hm8S1X42r/YWQ==" rel="stylesheet" href="https://assets-cdn.github.com/assets/site-220df28424b63d1e24f3bd909efebe81.css" />
  

  <meta name="viewport" content="width=device-width">
  
  <title>cosmos/WHITEPAPER.md at master · cosmos/cosmos · GitHub</title>
    <meta name="description" content="GitHub is where people build software. More than 28 million people use GitHub to discover, fork, and contribute to over 85 million projects.">
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    
    <meta property="og:image" content="https://avatars3.githubusercontent.com/u/228843?s=400&amp;v=4" /><meta property="og:site_name" content="GitHub" /><meta property="og:type" content="object" /><meta property="og:title" content="cosmos/cosmos" /><meta property="og:url" content="https://github.com/cosmos/cosmos" /><meta property="og:description" content="cosmos - ⚛ Internet of Blockchains" />

  <link rel="assets" href="https://assets-cdn.github.com/">
  
  <meta name="pjax-timeout" content="1000">
  
  <meta name="request-id" content="CF24:494E:276457:38EDD3:5B1FDD0B" data-pjax-transient>


  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
  <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
  <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">
    <meta name="google-analytics" content="UA-3769691-2">

<meta name="octolytics-host" content="collector.githubapp.com" /><meta name="octolytics-app-id" content="github" /><meta name="octolytics-event-url" content="https://collector.githubapp.com/github-external/browser_event" /><meta name="octolytics-dimension-request_id" content="CF24:494E:276457:38EDD3:5B1FDD0B" /><meta name="octolytics-dimension-region_edge" content="ap-southeast-1" /><meta name="octolytics-dimension-region_render" content="iad" />
<meta name="analytics-location" content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" />




  <meta class="js-ga-set" name="dimension1" content="Logged Out">


  

      <meta name="hostname" content="github.com">
    <meta name="user-login" content="">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="YmNkNzA5NDNmODUyYmEwYjZkYTcwN2UyODVkNmM3N2YzM2ZiMGJkNmEzYjdmMDAwODY3YzAwZDQwYTIyMzZmZHx7InJlbW90ZV9hZGRyZXNzIjoiMTgwLjE1OC4yMjQuMjM0IiwicmVxdWVzdF9pZCI6IkNGMjQ6NDk0RToyNzY0NTc6MzhFREQzOjVCMUZERDBCIiwidGltZXN0YW1wIjoxNTI4ODE0ODYzLCJob3N0IjoiZ2l0aHViLmNvbSJ9">

    <meta name="enabled-features" content="UNIVERSE_BANNER,FREE_TRIALS,MARKETPLACE_INSIGHTS,MARKETPLACE_INSIGHTS_CONVERSION_PERCENTAGES">

  <meta name="html-safe-nonce" content="9dc3229755a0482f53c90b8001caaa0f5b9d81c0">

  <meta http-equiv="x-pjax-version" content="8fa77f0da0512c800d9d302400c2f8de">
  

      <link href="https://github.com/cosmos/cosmos/commits/master.atom" rel="alternate" title="Recent Commits to cosmos:master" type="application/atom+xml">

  <meta name="description" content="cosmos - ⚛ Internet of Blockchains">
  <meta name="go-import" content="github.com/cosmos/cosmos git https://github.com/cosmos/cosmos.git">

  <meta name="octolytics-dimension-user_id" content="228843" /><meta name="octolytics-dimension-user_login" content="cosmos" /><meta name="octolytics-dimension-repository_id" content="59239387" /><meta name="octolytics-dimension-repository_nwo" content="cosmos/cosmos" /><meta name="octolytics-dimension-repository_public" content="true" /><meta name="octolytics-dimension-repository_is_fork" content="false" /><meta name="octolytics-dimension-repository_network_root_id" content="59239387" /><meta name="octolytics-dimension-repository_network_root_nwo" content="cosmos/cosmos" /><meta name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" content="false" />


    <link rel="canonical" href="https://github.com/cosmos/cosmos/blob/master/WHITEPAPER.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" class="js-site-favicon" href="https://assets-cdn.github.com/favicon.ico">

<meta name="theme-color" content="#1e2327">



<link rel="manifest" href="/manifest.json" crossOrigin="use-credentials">

  </head>

  <body class="logged-out env-production page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="px-2 py-4 bg-blue text-white show-on-focus js-skip-to-content">Skip to content</a>
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>

    
    
    



        <header class="Header header-logged-out  position-relative f4 py-3" role="banner">
  <div class="container-lg d-flex px-3">
    <div class="d-flex flex-justify-between flex-items-center">
      <a class="header-logo-invertocat my-0" href="https://github.com/" aria-label="Homepage" data-ga-click="(Logged out) Header, go to homepage, icon:logo-wordmark">
        <svg height="32" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
      </a>

    </div>

    <div class="HeaderMenu HeaderMenu--bright d-flex flex-justify-between flex-auto">
        <nav class="mt-0">
          <ul class="d-flex list-style-none">
              <li class="ml-2">
                <a class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:features" data-selected-links="/features /features/project-management /features/code-review /features/project-management /features/integrations /features" href="/features">
                  Features
</a>              </li>
              <li class="ml-4">
                <a class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:business" data-selected-links="/business /business/security /business/customers /business" href="/business">
                  Business
</a>              </li>

              <li class="ml-4">
                <a class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:explore" data-selected-links="/explore /trending /trending/developers /integrations /integrations/feature/code /integrations/feature/collaborate /integrations/feature/ship showcases showcases_search showcases_landing /explore" href="/explore">
                  Explore
</a>              </li>

              <li class="ml-4">
                    <a class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:marketplace" data-selected-links=" /marketplace" href="/marketplace">
                      Marketplace
</a>              </li>
              <li class="ml-4">
                <a class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:pricing" data-selected-links="/pricing /pricing/developer /pricing/team /pricing/business-hosted /pricing/business-enterprise /pricing" href="/pricing">
                  Pricing
</a>              </li>
          </ul>
        </nav>

      <div class="d-flex">
          <div class="d-lg-flex flex-items-center mr-3">
            <div class="header-search scoped-search site-scoped-search js-site-search position-relative" role="search">
  <div class="position-relative">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-site-search-form" data-scope-type="Repository" data-scope-id="59239387" data-scoped-search-url="/cosmos/cosmos/search" data-unscoped-search-url="/search" action="/cosmos/cosmos/search" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
      <label class="form-control header-search-wrapper  js-chromeless-input-container">
            <a class="header-search-scope no-underline" href="/cosmos/cosmos/blob/master/WHITEPAPER.md">This repository</a>
        <input type="text"
          class="form-control header-search-input  js-site-search-focus js-site-search-field is-clearable"
          data-hotkey="s,/"
          name="q"
          value=""
          placeholder="Search"
          aria-label="Search this repository"
          data-unscoped-placeholder="Search GitHub"
          data-scoped-placeholder="Search"
          autocapitalize="off"
          >
          <input type="hidden" class="js-site-search-type-field" name="type" >
      </label>
</form>  </div>
</div>

          </div>

        <span class="d-inline-block">
            <div class="HeaderNavlink px-0 py-2 m-0">
              <a class="text-bold text-white no-underline" href="/login?return_to=%2Fcosmos%2Fcosmos%2Fblob%2Fmaster%2FWHITEPAPER.md" data-ga-click="(Logged out) Header, clicked Sign in, text:sign-in">Sign in</a>
                <span class="text-gray">or</span>
                <a class="text-bold text-white no-underline" href="/join?source=header-repo" data-ga-click="(Logged out) Header, clicked Sign up, text:sign-up">Sign up</a>
            </div>
        </span>
      </div>
    </div>
  </div>
</header>

  </div>

  <div id="start-of-content" class="show-on-focus"></div>

    <div id="js-flash-container">
</div>



  <div role="main" class="application-main ">
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode" class="">
    <div id="js-repo-pjax-container" data-pjax-container >
      





  



  <div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav  ">
    <div class="repohead-details-container clearfix container">

      <ul class="pagehead-actions">
  <li>
      <a href="/login?return_to=%2Fcosmos%2Fcosmos"
    class="btn btn-sm btn-with-count tooltipped tooltipped-n"
    aria-label="You must be signed in to watch a repository" rel="nofollow">
    <svg class="octicon octicon-eye" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
    Watch
  </a>
  <a class="social-count" href="/cosmos/cosmos/watchers"
     aria-label="99 users are watching this repository">
    99
  </a>

  </li>

  <li>
      <a href="/login?return_to=%2Fcosmos%2Fcosmos"
    class="btn btn-sm btn-with-count tooltipped tooltipped-n"
    aria-label="You must be signed in to star a repository" rel="nofollow">
    <svg class="octicon octicon-star" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>
    Star
  </a>

    <a class="social-count js-social-count" href="/cosmos/cosmos/stargazers"
      aria-label="510 users starred this repository">
      510
    </a>

  </li>

  <li>
      <a href="/login?return_to=%2Fcosmos%2Fcosmos"
        class="btn btn-sm btn-with-count tooltipped tooltipped-n"
        aria-label="You must be signed in to fork a repository" rel="nofollow">
        <svg class="octicon octicon-repo-forked" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
        Fork
      </a>

    <a href="/cosmos/cosmos/network" class="social-count"
       aria-label="91 users forked this repository">
      91
    </a>
  </li>
</ul>

      <h1 class="public ">
  <svg class="octicon octicon-repo" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a class="url fn" rel="author" href="/cosmos">cosmos</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a data-pjax="#js-repo-pjax-container" href="/cosmos/cosmos">cosmos</a></strong>

</h1>

    </div>
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax container"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a class="js-selected-navigation-item selected reponav-item" itemprop="url" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /cosmos/cosmos" href="/cosmos/cosmos">
      <svg class="octicon octicon-code" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a itemprop="url" data-hotkey="g i" class="js-selected-navigation-item reponav-item" data-selected-links="repo_issues repo_labels repo_milestones /cosmos/cosmos/issues" href="/cosmos/cosmos/issues">
        <svg class="octicon octicon-issue-opened" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg>
        <span itemprop="name">Issues</span>
        <span class="Counter">23</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a data-hotkey="g p" itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /cosmos/cosmos/pulls" href="/cosmos/cosmos/pulls">
      <svg class="octicon octicon-git-pull-request" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">4</span>
      <meta itemprop="position" content="3">
</a>  </span>

    <a data-hotkey="g b" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /cosmos/cosmos/projects" href="/cosmos/cosmos/projects">
      <svg class="octicon octicon-project" viewBox="0 0 15 16" version="1.1" width="15" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      Projects
      <span class="Counter" >0</span>
</a>


  <a class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph pulse /cosmos/cosmos/pulse" href="/cosmos/cosmos/pulse">
    <svg class="octicon octicon-graph" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
    Insights
</a>

</nav>


  </div>

<div class="container new-discussion-timeline experiment-repo-nav  ">
  <div class="repository-content ">

    
  <a class="d-none js-permalink-shortcut" data-hotkey="y" href="/cosmos/cosmos/blob/8f6e52503bca78165dc4b41df124f76371be72c0/WHITEPAPER.md">Permalink</a>

  <!-- blob contrib key: blob_contributors:v21:cb5852b216eb283d8ff2e9f5891948ee -->

  <div class="file-navigation">
    
<div class="select-menu branch-select-menu js-menu-container js-select-menu float-left">
  <button class=" btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    
    type="button" aria-label="Switch branches or tags" aria-expanded="false" aria-haspopup="true">
      <i>Branch:</i>
      <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax>

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <svg class="octicon octicon-x js-menu-close" role="img" aria-label="Close" viewBox="0 0 12 16" version="1.1" width="12" height="16"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
        <span class="select-menu-title">Switch branches/tags</span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="form-control js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/cosmos/cosmos/blob/consensus/WHITEPAPER.md"
               data-name="consensus"
               data-skip-pjax="true"
               rel="nofollow">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                consensus
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/cosmos/cosmos/blob/fix_validators_faq/WHITEPAPER.md"
               data-name="fix_validators_faq"
               data-skip-pjax="true"
               rel="nofollow">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                fix_validators_faq
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/cosmos/cosmos/blob/gamarin2-patch-1/WHITEPAPER.md"
               data-name="gamarin2-patch-1"
               data-skip-pjax="true"
               rel="nofollow">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                gamarin2-patch-1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/cosmos/cosmos/blob/genesis_change/WHITEPAPER.md"
               data-name="genesis_change"
               data-skip-pjax="true"
               rel="nofollow">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                genesis_change
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/cosmos/cosmos/blob/ibc/WHITEPAPER.md"
               data-name="ibc"
               data-skip-pjax="true"
               rel="nofollow">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                ibc
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/cosmos/cosmos/blob/inflation/WHITEPAPER.md"
               data-name="inflation"
               data-skip-pjax="true"
               rel="nofollow">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                inflation
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/cosmos/cosmos/blob/intro/WHITEPAPER.md"
               data-name="intro"
               data-skip-pjax="true"
               rel="nofollow">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                intro
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/cosmos/cosmos/blob/lra/WHITEPAPER.md"
               data-name="lra"
               data-skip-pjax="true"
               rel="nofollow">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                lra
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/cosmos/cosmos/blob/master/WHITEPAPER.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                master
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/cosmos/cosmos/blob/mauve/WHITEPAPER.md"
               data-name="mauve"
               data-skip-pjax="true"
               rel="nofollow">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                mauve
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/cosmos/cosmos/blob/mediawiki/WHITEPAPER.md"
               data-name="mediawiki"
               data-skip-pjax="true"
               rel="nofollow">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                mediawiki
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/cosmos/cosmos/blob/questions/WHITEPAPER.md"
               data-name="questions"
               data-skip-pjax="true"
               rel="nofollow">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                questions
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/cosmos/cosmos/blob/research/WHITEPAPER.md"
               data-name="research"
               data-skip-pjax="true"
               rel="nofollow">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                research
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/cosmos/cosmos/blob/shards/WHITEPAPER.md"
               data-name="shards"
               data-skip-pjax="true"
               rel="nofollow">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                shards
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/cosmos/cosmos/blob/snapshot/WHITEPAPER.md"
               data-name="snapshot"
               data-skip-pjax="true"
               rel="nofollow">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                snapshot
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/cosmos/cosmos/blob/updates/WHITEPAPER.md"
               data-name="updates"
               data-skip-pjax="true"
               rel="nofollow">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                updates
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

    <div class="BtnGroup float-right">
      <a href="/cosmos/cosmos/find/master"
            class="js-pjax-capture-input btn btn-sm BtnGroup-item"
            data-pjax
            data-hotkey="t">
        Find file
      </a>
      <clipboard-copy for="blob-path" class="btn btn-sm BtnGroup-item">
        Copy path
      </clipboard-copy>
    </div>
    <div id="blob-path" class="breadcrumb">
      <span class="repo-root js-repo-root"><span class="js-path-segment"><a data-pjax="true" href="/cosmos/cosmos"><span>cosmos</span></a></span></span><span class="separator">/</span><strong class="final-path">WHITEPAPER.md</strong>
    </div>
  </div>


  <include-fragment src="/cosmos/cosmos/contributors/master/WHITEPAPER.md" class="commit-tease commit-loader">
    <div>
      Fetching contributors&hellip;
    </div>

    <div class="commit-tease-contributors">
        <img alt="" class="loader-loading float-left" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32-EAF2F5.gif" width="16" height="16" />
      <span class="loader-error">Cannot retrieve contributors at this time</span>
    </div>
</include-fragment>


  <div class="file">
    <div class="file-header">
  <div class="file-actions">

    <div class="BtnGroup">
      <a id="raw-url" class="btn btn-sm BtnGroup-item" href="/cosmos/cosmos/raw/master/WHITEPAPER.md">Raw</a>
        <a class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b" href="/cosmos/cosmos/blame/master/WHITEPAPER.md">Blame</a>
      <a rel="nofollow" class="btn btn-sm BtnGroup-item" href="/cosmos/cosmos/commits/master/WHITEPAPER.md">History</a>
    </div>


        <button type="button" class="btn-octicon disabled tooltipped tooltipped-nw"
          aria-label="You must be signed in to make or propose changes">
          <svg class="octicon octicon-pencil" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
        </button>
        <button type="button" class="btn-octicon btn-octicon-danger disabled tooltipped tooltipped-nw"
          aria-label="You must be signed in to make or propose changes">
          <svg class="octicon octicon-trashcan" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
        </button>
  </div>

  <div class="file-info">
      1680 lines (1398 sloc)
      <span class="file-info-divider"></span>
    86.7 KB
  </div>
</div>

    
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><h1><a id="user-content-cosmos" class="anchor" aria-hidden="true" href="#cosmos"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Cosmos</h1>
<p><strong>A Network of Distributed Ledgers</strong></p>
<p>Jae Kwon <a href="mailto:jae@tendermint.com">jae@tendermint.com</a><br>
Ethan Buchman <a href="mailto:ethan@tendermint.com">ethan@tendermint.com</a></p>
<p>For discussions, <a href="https://riot.im/app/#/room/#cosmos:matrix.org" rel="nofollow">join our chat</a>!</p>
<p><em>NOTE: If you can read this on GitHub, then we're still actively developing this
document.  Please check regularly for updates!</em></p>
<h2><a id="user-content-table-of-contents" class="anchor" aria-hidden="true" href="#table-of-contents"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Table of Contents</h2>
<ul>
<li><a href="#introduction">Introduction</a></li>
<li><a href="#tendermint">Tendermint</a>
<ul>
<li><a href="#validators">Validators</a></li>
<li><a href="#consensus">Consensus</a></li>
<li><a href="#light-clients">Light Clients</a></li>
<li><a href="#preventing-attacks">Preventing Attacks</a></li>
<li><a href="#abci">ABCI</a></li>
</ul>
</li>
<li><a href="#cosmos-overview">Cosmos Overview</a>
<ul>
<li><a href="#tendermint-bft">Tendermint-BFT</a></li>
<li><a href="#governance">Governance</a></li>
</ul>
</li>
<li><a href="#the-hub-and-zones">The Hub and Zones</a>
<ul>
<li><a href="#the-hub">The Hub</a></li>
<li><a href="#the-zones">The Zones</a></li>
</ul>
</li>
<li><a href="#inter-blockchain-communication-ibc">Inter-blockchain Communication (IBC)</a></li>
<li><a href="#use-cases">Use Cases</a>
<ul>
<li><a href="#distributed-exchange">Distributed Exchange</a></li>
<li><a href="#bridging-to-other-cryptocurrencies">Bridging to Other Cryptocurrencies</a></li>
<li><a href="#ethereum-scaling">Ethereum Scaling</a></li>
<li><a href="#multi-application-integration">Multi-Application Integration</a></li>
<li><a href="#network-partition-mitigation">Network Partition Mitigation</a></li>
<li><a href="#federated-name-resolution-system">Federated Name Resolution System</a></li>
</ul>
</li>
<li><a href="#issuance-and-incentives">Issuance and Incentives</a>
<ul>
<li><a href="#the-atom-token">The Atom Token</a>
<ul>
<li><a href="#fundraiser">Fundraiser</a></li>
</ul>
</li>
<li><a href="#limitations-on-the-number-of-validators">Limitations on the Number of
Validators</a></li>
<li><a href="#becoming-a-validator-after-genesis-day">Becoming a Validator after Genesis
Day</a></li>
<li><a href="#penalties-for-validators">Penalties for Validators</a></li>
<li><a href="#transaction-fees">Transaction Fees</a></li>
<li><a href="#incentivizing-hackers">Incentivizing Hackers</a></li>
</ul>
</li>
<li><a href="#governance-specification">Governance Specification</a>
<ul>
<li><a href="#parameter-change-proposal">Parameter Change Proposal</a></li>
<li><a href="#text-proposal">Text Proposal</a></li>
</ul>
</li>
<li><a href="#roadmap">Roadmap</a></li>
<li><a href="#related-work">Related Work</a>
<ul>
<li><a href="#consensus-systems">Consensus Systems</a>
<ul>
<li><a href="#classic-byzantine-fault-tolerance">Classic Byzantine Fault Tolerance</a></li>
<li><a href="#bitshares-delegated-stake">BitShares Delegated Stake</a></li>
<li><a href="#stellar">Stellar</a></li>
<li><a href="#bitcoinng">BitcoinNG</a></li>
<li><a href="#casper">Casper</a></li>
</ul>
</li>
<li><a href="#horizontal-scaling">Horizontal Scaling</a>
<ul>
<li><a href="#interledger-protocol">Interledger Protocol</a></li>
<li><a href="#sidechains">Sidechains</a></li>
<li><a href="#ethereum-scalability-efforts">Ethereum Scalability Efforts</a></li>
</ul>
</li>
<li><a href="#general-scaling">General Scaling</a>
<ul>
<li><a href="#lightning-network">Lightning Network</a></li>
<li><a href="#segregated-witness">Segregated Witness</a></li>
</ul>
</li>
</ul>
</li>
<li><a href="#appendix">Appendix</a>
<ul>
<li><a href="#fork-accountability">Fork Accountability</a></li>
<li><a href="#tendermint-consensus">Tendermint Consensus</a></li>
<li><a href="#tendermint-light-clients">Tendermint Light Clients</a></li>
<li><a href="#preventing-long-range-attacks">Preventing Long Range Attacks</a></li>
<li><a href="#overcoming-forks-and-censorship-attacks">Overcoming Forks and Censorship
Attacks</a></li>
<li><a href="#abci-specification">ABCI Specification</a></li>
<li><a href="#ibc-packet-delivery-acknowledgement">IBC Packet Delivery
Acknowledgement</a></li>
<li><a href="#merkle-tree--proof-specification">Merkle Tree &amp; Proof
Specification</a></li>
<li><a href="#transaction-types">Transaction Types</a>
<ul>
<li><a href="#ibcblockcommittx">IBCBlockCommitTx</a></li>
<li><a href="#ibcpackettx">IBCPacketTx</a></li>
</ul>
</li>
</ul>
</li>
<li><a href="#acknowledgements">Acknowledgements</a></li>
<li><a href="#citations">Citations</a></li>
</ul>
<h2><a id="user-content-introduction" class="anchor" aria-hidden="true" href="#introduction"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Introduction</h2>
<p>The combined success of the open-source ecosystem, decentralized
file-sharing, and public cryptocurrencies has inspired an understanding that
decentralized internet protocols can be used to radically improve socio-economic
infrastructure.  We have seen specialized blockchain applications like Bitcoin
<a href="https://bitcoin.org/bitcoin.pdf" rel="nofollow">[1]</a> (a cryptocurrency), Zerocash <a href="http://zerocash-project.org/paper" rel="nofollow">[2]</a> (a cryptocurrency for
privacy), and generalized smart contract platforms such as Ethereum <a href="https://github.com/ethereum/wiki/wiki/White-Paper">[3]</a>,
with countless distributed applications for the Ethereum Virtual Machine (EVM) such as Augur (a prediction
market) and TheDAO <a href="https://download.slock.it/public/DAO/WhitePaper.pdf" rel="nofollow">[4]</a> (an investment club).</p>
<p>To date, however, these blockchains have suffered from a number of drawbacks,
including their gross energy inefficiency, poor or limited performance, and
immature governance mechanisms.  Proposals to scale
Bitcoin's transaction throughput, such as Segregated-Witness <a href="https://github.com/bitcoin/bips/blob/master/bip-0141.mediawiki">[5]</a> and
BitcoinNG <a href="https://arxiv.org/pdf/1510.02037v2.pdf" rel="nofollow">[6]</a>, are vertical scaling solutions that remain
limited by the capacity of a single physical machine, in order to ensure the
property of complete auditability.  The Lightning Network <a href="https://lightning.network/lightning-network-paper-DRAFT-0.5.pdf" rel="nofollow">[7]</a> can help
scale Bitcoin transaction volume by leaving some transactions off the ledger
completely, and is well suited for micropayments and privacy-preserving payment
rails, but may not be suitable for more generalized scaling needs.</p>
<p>An ideal solution is one that allows multiple parallel blockchains to
interoperate while retaining their security properties. This has proven
difficult, if not impossible, with proof-of-work. Merged mining, for instance,
allows the work done to secure a parent chain to be reused on a child chain,
but transactions must still be validated, in order, by each node, and a
merge-mined blockchain is vulnerable to attack if a majority of the hashing
power on the parent is not actively merge-mining the child.  An academic review
of <a href="http://vukolic.com/iNetSec_2015.pdf" rel="nofollow">alternative blockchain network
architectures</a> is provided for additional
context, and we provide summaries of other proposals and their drawbacks in
<a href="#related-work">Related Work</a>.</p>
<p>Here we present Cosmos, a novel blockchain network architecture that addresses all
of these problems.  Cosmos is a network connecting many independent blockchains, called
zones.  The zones are powered by Tendermint Core <a href="https://github.com/tendermint/tendermint/wiki">[8]</a>, which provides a
high-performance, consistent, secure
<a href="http://tendermint.com/blog/tendermint-vs-pbft/" rel="nofollow">PBFT-like</a> consensus engine,
where strict <a href="#fork-accountability">fork-accountability</a> guarantees hold over
the behaviour of malicious actors.  Tendermint Core's BFT consensus algorithm is
well suited for scaling public proof-of-stake blockchains.  Blockchains with other consensus models, including proof-of-work blockchains like Ethereum and Bitcoin can be connected to the Cosmos network using adapter zones.</p>
<p>The first zone on Cosmos is called the Cosmos Hub. The Cosmos Hub is a
multi-asset proof-of-stake cryptocurrency with a simple governance mechanism
which enables the network to adapt and upgrade.  In addition, the Cosmos Hub can be
extended by connecting other zones.</p>
<p>The hub and zones of the Cosmos network communicate with each other via an
inter-blockchain communication (IBC) protocol, a kind of virtual UDP or TCP for
blockchains.  Tokens can be transferred from one zone to another securely and
quickly without the need for exchange liquidity between zones.  Instead, all
inter-zone token transfers go through the Cosmos Hub, which keeps track of the
total amount of tokens held by each zone.  The hub isolates each zone from the
failure of other zones.  Because anyone can connect a new zone to the Cosmos Hub,
zones allow for future-compatibility with new blockchain innovations.</p>
<p>With Cosmos interoperability between blockchains can be achieved. The potential of an internet of value, where assets are issued and controlled by different sets of validators, yet can be moved and exchanged seamlessly between blockchains without relying on trusted third parties can be realized.</p>
<h2><a id="user-content-tendermint" class="anchor" aria-hidden="true" href="#tendermint"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Tendermint</h2>
<p>In this section we describe the Tendermint consensus protocol and the interface
used to build applications with it. For more details, see the <a href="#appendix">appendix</a>.</p>
<h3><a id="user-content-validators" class="anchor" aria-hidden="true" href="#validators"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Validators</h3>
<p>In classical Byzantine fault-tolerant (BFT) algorithms, each node has the same
weight.  In Tendermint, nodes have a non-negative amount of <em>voting power</em>, and
nodes that have positive voting power are called <em>validators</em>.  Validators
participate in the consensus protocol by broadcasting cryptographic signatures,
or <em>votes</em>, to agree upon the next block.</p>
<p>Validators' voting powers are determined at genesis, or are changed
deterministically by the blockchain, depending on the application.  For example,
in a proof-of-stake application such as the Cosmos Hub, the voting power may be
determined by the amount of staking tokens bonded as collateral.</p>
<p><em>NOTE: Fractions like ⅔ and ⅓ refer to fractions of the total voting power,
never the total number of validators, unless all the validators have equal
weight. &gt;⅔ means "more than ⅔", ≥⅓ means "at least ⅓".</em></p>
<h3><a id="user-content-consensus" class="anchor" aria-hidden="true" href="#consensus"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Consensus</h3>
<p>Tendermint is a partially synchronous BFT consensus protocol derived from the
DLS consensus algorithm <a href="http://groups.csail.mit.edu/tds/papers/Lynch/jacm88.pdf" rel="nofollow">[20]</a>. Tendermint is notable for its simplicity,
performance, and <a href="#fork-accountability">fork-accountability</a>.  The protocol
requires a fixed known set of validators, where each validator is identified by
their public key.  Validators attempt to come to consensus on one block at a time,
where a block is a list of transactions.  Voting for consensus on a block proceeds in
rounds. Each round has a round-leader, or proposer, who proposes a block. The
validators then vote, in stages, on whether to accept the proposed block
or move on to the next round. The proposer for a round is chosen
deterministically from the ordered list of validators, in proportion to their
voting power.</p>
<p>The full details of the protocol are described
<a href="https://github.com/tendermint/tendermint/wiki/Byzantine-Consensus-Algorithm">here</a>.</p>
<p>Tendermint’s security derives from its use of optimal Byzantine fault-tolerance
via super-majority (&gt;⅔) voting and a locking mechanism.  Together, they ensure
that:</p>
<ul>
<li>≥⅓ voting power must be Byzantine to cause a violation of safety, where more
than two values are committed.</li>
<li>if any set of validators ever succeeds in violating safety, or even attempts
to do so, they can be identified by the protocol.  This includes both voting
for conflicting blocks and broadcasting unjustified votes.</li>
</ul>
<p>Despite its strong guarantees, Tendermint provides exceptional performance.  In
benchmarks of 64 nodes distributed across 7 datacenters on 5 continents, on
commodity cloud instances, Tendermint consensus can process thousands of
transactions per second, with commit latencies on the order of one to two
seconds.  Notably, performance of well over a thousand transactions per second
is maintained even in harsh adversarial conditions, with validators crashing or
broadcasting maliciously crafted votes.  See the figure below for details.</p>
<p><a target="_blank" href="https://raw.githubusercontent.com/gnuclear/atom-whitepaper/master/images/tendermint_throughput_blocksize.png"><img src="https://raw.githubusercontent.com/gnuclear/atom-whitepaper/master/images/tendermint_throughput_blocksize.png" alt="Figure of Tendermint throughput performance" style="max-width:100%;"></a></p>
<h3><a id="user-content-light-clients" class="anchor" aria-hidden="true" href="#light-clients"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Light Clients</h3>
<p>A major benefit of Tendermint's consensus algorithm is simplified light client
security, making it an ideal candidate for mobile and internet-of-things use
cases.  While a Bitcoin light client must sync chains of block headers and find
the one with the most proof of work, Tendermint light clients need only to keep
up with changes to the validator set, and then verify the &gt;⅔ PreCommits
in the latest block to determine the latest state.</p>
<p>Succinct light client proofs also enable <a href="#inter-blockchain-communication-ibc">inter-blockchain
communication</a>.</p>
<h3><a id="user-content-preventing-attacks" class="anchor" aria-hidden="true" href="#preventing-attacks"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Preventing Attacks</h3>
<p>Tendermint has protective measures for preventing certain notable
attacks, like <a href="#preventing-long-range-attacks">long-range-nothing-at-stake double
spends</a> and
<a href="#overcoming-forks-and-censorship-attacks">censorship</a>. These are discussed more
fully in the <a href="#appendix">appendix</a>.</p>
<h3><a id="user-content-abci" class="anchor" aria-hidden="true" href="#abci"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>ABCI</h3>
<p>The Tendermint consensus algorithm is implemented in a program called Tendermint
Core.  Tendermint Core is an application-agnostic "consensus engine" that can
turn any deterministic blackbox application into a distributedly replicated
blockchain. Tendermint Core connects to blockchain
applications via the Application Blockchain Interface (ABCI) <a href="https://github.com/tendermint/abci">[17]</a>. Thus, ABCI
allows for blockchain applications to be programmed in any language, not just
the programming language that the consensus engine is written in.  Additionally,
ABCI makes it possible to easily swap out the consensus layer of any existing
blockchain stack.</p>
<p>We draw an analogy with the well-known cryptocurrency Bitcoin. Bitcoin is a
cryptocurrency blockchain where each node maintains a fully audited Unspent
Transaction Output (UTXO) database. If one wanted to create a Bitcoin-like
system on top of ABCI, Tendermint Core would be responsible for</p>
<ul>
<li>Sharing blocks and transactions between nodes</li>
<li>Establishing a canonical/immutable order of transactions (the blockchain)</li>
</ul>
<p>Meanwhile, the ABCI application would be responsible for</p>
<ul>
<li>Maintaining the UTXO database</li>
<li>Validating cryptographic signatures of transactions</li>
<li>Preventing transactions from spending non-existent funds</li>
<li>Allowing clients to query the UTXO database</li>
</ul>
<p>Tendermint is able to decompose the blockchain design by offering a very simple
API between the application process and consensus process.</p>
<h2><a id="user-content-cosmos-overview" class="anchor" aria-hidden="true" href="#cosmos-overview"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Cosmos Overview</h2>
<p>Cosmos is a network of independent parallel blockchains that are each powered by
classical BFT consensus algorithms like Tendermint
<a href="http://github.com/tendermint/tendermint">1</a>.</p>
<p>The first blockchain in this network will be the Cosmos Hub.  The Cosmos Hub
connects to many other blockchains (or <em>zones</em>) via a novel inter-blockchain
communication protocol.  The Cosmos Hub tracks numerous token types and keeps
record of the total number of tokens in each connected zone.  Tokens can be
transferred from one zone to another securely and quickly without the need for
a liquid exchange between zones, because all inter-zone coin transfers go
through the Cosmos Hub.</p>
<p>This architecture solves many problems that the blockchain space faces today,
such as application interoperability, scalability, and seamless upgradability.
For example, zones derived from Bitcoind, Go-Ethereum, CryptoNote, ZCash, or any
blockchain system can be plugged into the Cosmos Hub.  These zones allow Cosmos
to scale infinitely to meet global transaction demand.  Zones are also a great
fit for a distributed exchange, which will be supported as well.</p>
<p>Cosmos is not just a single distributed ledger, and the Cosmos Hub isn't a
walled garden or the center of its universe.  We are designing a protocol for
an open network of distributed ledgers that can serve as a new foundation for
future financial systems, based on principles of cryptography, sound economics,
consensus theory, transparency, and accountability.</p>
<h3><a id="user-content-tendermint-bft" class="anchor" aria-hidden="true" href="#tendermint-bft"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Tendermint-BFT</h3>
<p>The Cosmos Hub is the first public blockchain in the Cosmos Network, powered by
Tendermint's BFT consensus algorithm.  The Tendermint open-source project was
born in 2014 to address the speed, scalability, and environmental issues of
Bitcoin's proof-of-work consensus algorithm.  By using and improving upon
proven BFT algorithms developed at MIT in 1988 <a href="http://groups.csail.mit.edu/tds/papers/Lynch/jacm88.pdf" rel="nofollow">[20]</a>, the Tendermint
team was the first to conceptually demonstrate a proof-of-stake cryptocurrency
that addresses the nothing-at-stake problem suffered by first-generation
proof-of-stake cryptocurrencies such as NXT and BitShares1.0.</p>
<p>Today, practically all Bitcoin mobile wallets use trusted servers to provide
them with transaction verification.  This is because proof-of-work requires
waiting for many confirmations before a transaction can be considered
irreversibly committed.  Double-spend attacks have already been demonstrated on
services like CoinBase.</p>
<p>Unlike other blockchain consensus systems, Tendermint offers instant and
provably secure mobile-client payment verification. Since the Tendermint is
designed to never fork at all, mobile wallets can receive instant transaction
confirmation, which makes trustless and practical payments a reality on
smartphones.  This has significant ramifications for Internet of Things applications as well.</p>
<p>Validators in Cosmos have a similar role to Bitcoin miners, but instead use
cryptographic signatures to vote. Validators are secure, dedicated machines
that are responsible for committing blocks.  Non-validators can delegate their
staking tokens (called "atoms") to any validator to earn a portion of block fees
and atom rewards, but they incur the risk of getting punished (slashed) if the
delegate validator gets hacked or violates the protocol.  The proven safety
guarantees of Tendermint BFT consensus, and the collateral deposit of
stakeholders--validators and delegators--provide provable, quantifiable
security for nodes and light clients.</p>
<h3><a id="user-content-governance" class="anchor" aria-hidden="true" href="#governance"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Governance</h3>
<p>Distributed public ledgers should have a constitution and a governance system.
Bitcoin relies on the Bitcoin Foundation and mining to
coordinate upgrades, but this is a slow process.  Ethereum split into ETH and
ETC after hard-forking to address TheDAO hack, largely because there was no
prior social contract nor mechanism for making such decisions.</p>
<p>Validators and delegators on the Cosmos Hub can vote on proposals that can
change preset parameters of the system automatically (such as the block gas
limit), coordinate upgrades, as well as vote on amendments to the human-readable
constitution that govern the policies of the Cosmos Hub.  The constitution
allows for cohesion among the stakeholders on issues such as theft
and bugs (such as TheDAO incident), allowing for quicker and cleaner resolution.</p>
<p>Each zone can also have their own constitution and governance mechanism as well.
For example, the Cosmos Hub could have a constitution that enforces immutability
at the Hub (no roll-backs, save for bugs of the Cosmos Hub node implementation),
while each zone can set their own policies regarding roll-backs.</p>
<p>By enabling interoperability among differing policy zones, the Cosmos network
gives its users ultimate freedom and potential for permissionless
experimentation.</p>
<h2><a id="user-content-the-hub-and-zones" class="anchor" aria-hidden="true" href="#the-hub-and-zones"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>The Hub and Zones</h2>
<p>Here we describe a novel model of decentralization and scalability.  Cosmos is a
network of many blockchains powered by Tendermint.  While existing proposals aim
to create a "single blockchain" with total global transaction ordering, Cosmos
permits many blockchains to run concurrently with one another while retaining
interoperability.</p>
<p>At the basis, the Cosmos Hub manages many independent blockchains called "zones"
(sometimes referred to as "shards", in reference to the database scaling
technique known as "sharding").  A constant stream of recent block commits from
zones posted on the Hub allows the Hub to keep up with the state of each zone.
Likewise, each zone keeps up with the state of the Hub (but zones do not keep up
with each other except indirectly through the Hub).  Packets of information are
then communicated from one zone to another by posting Merkle-proofs as evidence
that the information was sent and received.  This mechanism is called
inter-blockchain communication, or IBC for short.</p>
<p><a target="_blank" href="https://raw.githubusercontent.com/gnuclear/atom-whitepaper/master/images/hub_and_zones.png"><img src="https://raw.githubusercontent.com/gnuclear/atom-whitepaper/master/images/hub_and_zones.png" alt="Figure of hub and zones acknowledgement" style="max-width:100%;"></a></p>
<p>Any of the zones can themselves be hubs to form an acyclic graph, but
for the sake of clarity we will only describe the simple configuration where
there is only one hub, and many non-hub zones.</p>
<h3><a id="user-content-the-hub" class="anchor" aria-hidden="true" href="#the-hub"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>The Hub</h3>
<p>The Cosmos Hub is a blockchain that hosts a multi-asset distributed ledger,
where tokens can be held by individual users or by zones themselves.  These
tokens can be moved from one zone to another in a special IBC packet called a
"coin packet".  The hub is responsible for preserving the global invariance of
the total amount of each token across the zones. IBC coin packet transactions
must be committed by the sender, hub, and receiver blockchains.</p>
<p>Since the Cosmos Hub acts as the central ledger for the whole
system, the security of the Hub is of paramount importance.  While each
zone may be a Tendermint blockchain that is secured by as few as 4 (or even
less if BFT consensus is not needed), the Hub must be secured by a globally
decentralized set of validators that can withstand the most severe attack
scenarios, such as a continental network partition or a nation-state sponsored
attack.</p>
<h3><a id="user-content-the-zones" class="anchor" aria-hidden="true" href="#the-zones"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>The Zones</h3>
<p>A Cosmos zone is an independent blockchain that exchanges IBC messages with the
Hub.  From the Hub's perspective, a zone is a multi-asset dynamic-membership
multi-signature account that can send and receive tokens using IBC packets. Like
a cryptocurrency account, a zone cannot transfer more tokens than it has, but
can receive tokens from others who have them. A zone may be designated as an
"source" of one or more token types, granting it the power to inflate that token
supply.</p>
<p>Atoms of the Cosmos Hub may be staked by validators of a zone connected to the
Hub.  While double-spend attacks on these zones would result in the slashing of
atoms with Tendermint's fork-accountability, a zone where &gt;⅔ of the voting power
are Byzantine can commit invalid state.  The Cosmos Hub does not verify or
execute transactions committed on other zones, so it is the responsibility of
users to send tokens to zones that they trust.  In the future, the Cosmos Hub's
governance system may pass Hub improvement proposals that account for zone
failures.  For example, outbound token transfers from some (or all) zones may be
throttled to allow for the emergency circuit-breaking of zones (a temporary halt
of token transfers) when an attack is detected.</p>
<h2><a id="user-content-inter-blockchain-communication-ibc" class="anchor" aria-hidden="true" href="#inter-blockchain-communication-ibc"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Inter-blockchain Communication (IBC)</h2>
<p>Now we look at how the Hub and zones communicate with each other.  For example, if
there are three blockchains, "Zone1", "Zone2", and "Hub", and we wish for
"Zone1" to produce a packet destined for "Zone2" going through "Hub". To move a
packet from one blockchain to another, a proof is posted on the
receiving chain. The proof states that the sending chain published a packet for the alleged
destination. For the receiving chain to check this proof, it must be able keep
up with the sender's block headers.  This mechanism is similar to that used by
sidechains, which requires two interacting chains to be aware of one another via a
bidirectional stream of proof-of-existence datagrams (transactions).</p>
<p>The IBC protocol can naturally be defined using two types of transactions: an
<code>IBCBlockCommitTx</code> transaction, which allows a blockchain to prove to any
observer of its most recent block-hash, and an <code>IBCPacketTx</code> transaction, which
allows a blockchain to prove to any observer that the given packet was indeed
published by the sender's application, via a Merkle-proof to the recent
block-hash.</p>
<p>By splitting the IBC mechanics into two separate transactions, we allow the
native fee market-mechanism of the receiving chain to determine which packets
get committed (i.e. acknowledged), while allowing for complete freedom on the
sending chain as to how many outbound packets are allowed.</p>
<p><a target="_blank" href="https://raw.githubusercontent.com/gnuclear/atom-whitepaper/master/msc/ibc_without_ack.png"><img src="https://raw.githubusercontent.com/gnuclear/atom-whitepaper/master/msc/ibc_without_ack.png" alt="Figure of Zone1, Zone2, and Hub IBC without acknowledgement" style="max-width:100%;"></a></p>
 In the example above, in order to update the block-hash of
"Zone1" on "Hub" (or of "Hub" on "Zone2"), an `IBCBlockCommitTx`
transaction must be posted on "Hub" with the block-hash of "Zone1" (or on
"Zone2" with the block-hash of "Hub").
<p><em>See <a href="#ibcblockcommittx">IBCBlockCommitTx</a> and <a href="#ibcpacketcommit">IBCPacketTx</a>
for for more information on the two IBC transaction types.</em></p>
<h2><a id="user-content-use-cases" class="anchor" aria-hidden="true" href="#use-cases"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Use Cases</h2>
<h3><a id="user-content-distributed-exchange" class="anchor" aria-hidden="true" href="#distributed-exchange"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Distributed Exchange</h3>
<p>In the same way that Bitcoin is more secure by being a distributed,
mass-replicated ledger, we can make exchanges less vulnerable to external and
internal hacks by running it on the blockchain.  We call this a distributed
exchange.</p>
<p>What the cryptocurrency community calls a decentralized exchange today are
based on something called "atomic cross-chain" (AXC) transactions.  With an AXC
transaction, two users on two different chains can make two transfer
transactions that are committed together on both ledgers, or none at all (i.e.
atomically).  For example, two users can trade bitcoins for ether (or any two
tokens on two different ledgers) using AXC transactions, even though Bitcoin
and Ethereum are not connected to each other.  The benefit of running an
exchange on AXC transactions is that neither users need to trust each other or
the trade-matching service.  The downside is that both parties need to be
online for the trade to occur.</p>
<p>Another type of decentralized exchange is a mass-replicated distributed
exchange that runs on its own blockchain.  Users on this kind of exchange can
submit a limit order and turn their computer off, and the trade can execute
without the user being online.  The blockchain matches and completes the trade
on behalf of the trader.</p>
<p>A centralized exchange can create a deep orderbook of limit orders and thereby
attract more traders.  Liquidity begets more liquidity in the exchange world,
and so there is a strong network effect (or at least a winner-take-most effect)
in the exchange business.  The current leader for cryptocurrency exchanges
today is Poloniex with a 24-hour volume of $20M, and in second place is
Bitfinex with a 24-hour volume of $5M.  Given such strong network effects, it
is unlikely for AXC-based decentralized exchanges to win volume over the
centralized exchanges.  For a decentralized exchange to compete with a
centralized exchange, it would need to support deep orderbooks with limit
orders.  Only a distributed exchange on a blockchain can provide that.</p>
<p>Tendermint provides additional benefits of faster transaction commits.  By
prioritizing fast finality without sacrificing consistency, zones in Cosmos can
finalize transactions fast -- for both exchange order transactions as well as
IBC token transfers to and from other zones.</p>
<p>Given the state of cryptocurrency exchanges today, a great application for
Cosmos is the distributed exchange (aka the Cosmos DEX).  The transaction
throughput capacity as well as commit latency can be comparable to those of
centralized exchanges.  Traders can submit limit orders that can be executed
without both parties having to be online.  And with Tendermint, the Cosmos hub,
and IBC, traders can move funds in and out of the exchange to and from other
zones with speed.</p>
<h3><a id="user-content-bridging-to-other-cryptocurrencies" class="anchor" aria-hidden="true" href="#bridging-to-other-cryptocurrencies"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Bridging to Other Cryptocurrencies</h3>
<p>A privileged zone can act as the source of a bridged token of another
cryptocurrency. A bridge is similar to the relationship between a
Cosmos hub and zone; both must keep up with the latest blocks of the
other in order to verify proofs that tokens have moved from one to the other.  A
"bridge-zone" on the Cosmos network keeps up with the Hub as well as the
other cryptocurrency.  The indirection through the bridge-zone allows the logic of
the Hub to remain simple and agnostic to other blockchain consensus strategies
such as Bitcoin's proof-of-work mining.</p>
<h4><a id="user-content-sending-tokens-to-the-cosmos-hub" class="anchor" aria-hidden="true" href="#sending-tokens-to-the-cosmos-hub"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Sending Tokens to the Cosmos Hub</h4>
<p>Each bridge-zone validator would run a Tendermint-powered blockchain with a special
ABCI bridge-app, but also a full-node of the "origin" blockchain.</p>
<p>When new blocks are mined on the origin, the bridge-zone validators will come
to agreement on committed blocks by signing and sharing their respective local
view of the origin's blockchain tip.  When a bridge-zone receives payment on the
origin (and sufficient confirmations were agreed to have been seen in the case
of a PoW chain such as Ethereum or Bitcoin), a corresponding account is created
on the bridge-zone with that balance.</p>
<p>In the case of Ethereum, the bridge-zone can share the same validator-set as the
Cosmos Hub.  On the Ethereum side (the origin), a bridge-contract would allow
ether holders to send ether to the bridge-zone by sending it to the bridge-contract
on Ethereum.  Once ether is received by the bridge-contract, the ether cannot be
withdrawn unless an appropriate IBC packet is received by the bridge-contract from
the bridge-zone.  The bridge-contract tracks the validator-set of the bridge-zone, which
may be identical to the Cosmos Hub's validator-set.</p>
<p>In the case of Bitcoin, the concept is similar except that instead of a single
bridge-contract, each UTXO would be controlled by a threshold multisignature P2SH
pubscript.  Due to the limitations of the P2SH system, the signers cannot be
identical to the Cosmos Hub validator-set.</p>
<h4><a id="user-content-withdrawing-tokens-from-cosmos-hub" class="anchor" aria-hidden="true" href="#withdrawing-tokens-from-cosmos-hub"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Withdrawing Tokens from Cosmos Hub</h4>
<p>Ether on the bridge-zone ("bridged-ether") can be transferred to and from the
Hub, and later be destroyed with a transaction that sends it to a particular
withdrawal address on Ethereum. An IBC packet proving that the transaction
occurred on the bridge-zone can be posted to the Ethereum bridge-contract to
allow the ether to be withdrawn.</p>
<p>In the case of Bitcoin, the restricted scripting system makes it difficult to
mirror the IBC coin-transfer mechanism.  Each UTXO has its own independent
pubscript, so every UTXO must be migrated to a new UTXO when there is a change
in the set of Bitcoin escrow signers. One solution is to compress and
decompress the UTXO-set as necessary to keep the total number of UTXOs down.</p>
<h4><a id="user-content-total-accountability-of-bridge-zones" class="anchor" aria-hidden="true" href="#total-accountability-of-bridge-zones"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Total Accountability of Bridge Zones</h4>
<p>The risk of such a bridgeging contract is a rogue validator set.  ≥⅓ Byzantine
voting power could cause a fork, withdrawing ether from the bridge-contract on
Ethereum while keeping the bridged-ether on the bridge-zone. Worse, &gt;⅔ Byzantine
voting power can steal ether outright from those who sent it to the
bridge-contract by deviating from the original bridgeging logic of the bridge-zone.</p>
<p>It is possible to address these issues by designing the bridge to be totally
accountable.  For example, all IBC packets, from the hub and the origin, might
require acknowledgement by the bridge-zone in such a way that all state
transitions of the bridge-zone can be efficiently challenged and verified by
either the hub or the origin's bridge-contract.  The Hub and the origin should
allow the bridge-zone validators to post collateral, and token transfers out of
the bridge-contract should be delayed (and collateral unbonding period
sufficiently long) to allow for any challenges to be made by independent
auditors.  We leave the design of the specification and implementation of this
system open as a future Cosmos improvement proposal, to be passed by the Cosmos
Hub's governance system.</p>
<h3><a id="user-content-ethereum-scaling" class="anchor" aria-hidden="true" href="#ethereum-scaling"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Ethereum Scaling</h3>
<p>Solving the scaling problem is an open issue for Ethereum.  Currently,
Ethereum nodes process every single transaction and also store all the states.
<a href="https://docs.google.com/presentation/d/1CjD0W4l4-CwHKUvfF5Vlps76fKLEC6pIwu1a_kC_YRQ/mobilepresent?slide=id.gd284b9333_0_28" rel="nofollow">link</a>.</p>
<p>Since Tendermint can commit blocks much faster than Ethereum's proof-of-work,
EVM zones powered by Tendermint consensus and operating on bridged-ether can
provide higher performance to Ethereum blockchains.  Additionally, though the
Cosmos Hub and IBC packet mechanics does not allow for arbitrary contract logic
execution per se, it can be used to coordinate token movements between Ethereum
contracts running on different zones, providing a foundation for token-centric
Ethereum scaling via sharding.</p>
<h3><a id="user-content-multi-application-integration" class="anchor" aria-hidden="true" href="#multi-application-integration"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Multi-Application Integration</h3>
<p>Cosmos zones run arbitrary application logic, which is defined at the beginning of the
zone's life and can potentially be updated over time by governance. Such flexibility
allows Cosmos zones to act as bridges to other cryptocurrencies such as Ethereum or
Bitcoin, and it also permits derivatives of those blockchains, utilizing the
same codebase but with a different validator set and initial distribution. This
allows many existing cryptocurrency frameworks, such as those of Ethereum,
Zerocash, Bitcoin, CryptoNote and so on, to be used with Tendermint Core,
which is a higher performance consensus engine, on a common network, opening tremendous
opportunity for interoperability across platforms.  Furthermore, as a
multi-asset blockchain, a single transaction may contain multiple inputs and
outputs, where each input can be any token type, enabling Cosmos to serve
directly as a platform for decentralized exchange, though orders are assumed to
be matched via other platforms. Alternatively, a zone can serve as a distributed
fault-tolerant exchange (with orderbooks), which can be a strict improvement
over existing centralized cryptocurrency exchanges which tend to get hacked over
time.</p>
<p>Zones can also serve as blockchain-backed versions of enterprise and government
systems, where pieces of a particular service that are traditionally run by an
organization or group of organizations are instead run as a ABCI application on
a certain zone, which allows it to inherit the security and interoperability of the
public Cosmos network without sacrificing control over the underlying service.
Thus, Cosmos may offer the best of both worlds for organizations looking to
utilize blockchain technology but who are wary of relinquishing control completely
to a distributed third party.</p>
<h3><a id="user-content-network-partition-mitigation" class="anchor" aria-hidden="true" href="#network-partition-mitigation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Network Partition Mitigation</h3>
<p>Some claim that a major problem with consistency-favouring consensus algorithms
like Tendermint is that any network partition which causes there to be no single
partition with &gt;⅔ voting power (e.g. ≥⅓ going offline) will halt consensus
altogether. The Cosmos architecture can help mitigate this problem by using a global
hub with regional autonomous zones, where voting power for each zone are
distributed based on a common geographic region.  For instance, a common
paradigm may be for individual cities, or regions, to operate their own zones
while sharing a common hub (e.g. the Cosmos Hub), enabling municipal activity to
persist in the event that the hub halts due to a temporary network partition.
Note that this allows real geological, political, and network-topological
features to be considered in designing robust federated fault-tolerant systems.</p>
<h3><a id="user-content-federated-name-resolution-system" class="anchor" aria-hidden="true" href="#federated-name-resolution-system"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Federated Name Resolution System</h3>
<p>NameCoin was one of the first blockchains to attempt to solve the
name-resolution problem by adapting the Bitcoin blockchain.  Unfortunately there
have been several issues with this approach.</p>
<p>With Namecoin, we can verify that, for example, <em>@satoshi</em> was registered with a
particular public key at some point in the past, but we wouldn’t know whether
the public key had since been updated recently unless we download all the blocks
since the last update of that name.  This is due to the limitation of Bitcoin's
UTXO transaction Merkle-ization model, where only the transactions (but not
mutable application state) are Merkle-ized into the block-hash. This lets us
prove existence, but not the non-existence of later updates to a name.  Thus, we
can't know for certain the most recent value of a name without trusting a full
node, or incurring significant costs in bandwidth by downloading the whole
blockchain.</p>
<p>Even if a Merkle-ized search tree were implemented in NameCoin, its dependency
on proof-of-work makes light client verification problematic. Light clients must
download a complete copy of the headers for all blocks in the entire blockchain
(or at least all the headers since the last update to a name).  This means that
the bandwidth requirements scale linearly with the amount of time <a href="https://en.bitcoin.it/wiki/Thin_Client_Security" rel="nofollow">[21]</a>.
In addition, name-changes on a proof-of-work blockchain requires waiting for
additional proof-of-work confirmation blocks, which can take up to an hour on
Bitcoin.</p>
<p>With Tendermint, all we need is the most recent block-hash signed by a quorum of
validators (by voting power), and a Merkle proof to the current value associated
with the name.  This makes it possible to have a succinct, quick, and secure
light-client verification of name values.</p>
<p>In Cosmos, we can take this concept and extend it further. Each
name-registration zone in Cosmos can have an associated top-level-domain
(TLD) name such as ".com" or ".org", and each name-registration zone can have
its own governance and registration rules.</p>
<h2><a id="user-content-issuance-and-incentives" class="anchor" aria-hidden="true" href="#issuance-and-incentives"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Issuance and Incentives</h2>
<h3><a id="user-content-the-atom-token" class="anchor" aria-hidden="true" href="#the-atom-token"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>The Atom Token</h3>
<p>While the Cosmos Hub is a multi-asset distributed ledger, there is a special
native token called the <em>atom</em>.  Atoms are the only staking token of the Cosmos
Hub.  Atoms are a license for the holder to vote, validate, or delegate to other
validators.  Like Ethereum's ether, atoms can also be used to pay for
transaction fees to mitigate spam.  Additional inflationary atoms and block
transaction fees are rewarded to validators and delegators who delegate to
validators.</p>
<p>The <code>BurnAtomTx</code> transaction can be used to recover any proportionate amount of
tokens from the reserve pool.</p>
<h4><a id="user-content-fundraiser" class="anchor" aria-hidden="true" href="#fundraiser"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Fundraiser</h4>
<p>The initial distribution of atom tokens and validators on Genesis will go to the
donors of the Cosmos Fundraiser (75%), lead donors (5%), Cosmos Network
Foundation (10%), and ALL IN BITS, Inc (10%).  From genesis onward, 1/3 of the
total amount of atoms will be rewarded to bonded validators and delegators
every year.</p>
<p>See the <a href="https://github.com/cosmos/cosmos/blob/master/PLAN.md">Cosmos Plan</a>
for additional details.</p>
<h3><a id="user-content-limitations-on-the-number-of-validators" class="anchor" aria-hidden="true" href="#limitations-on-the-number-of-validators"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Limitations on the Number of Validators</h3>
<p>Unlike Bitcoin or other proof-of-work blockchains, a Tendermint blockchain gets
slower with more validators due to the increased communication complexity.
Fortunately, we can support enough validators to make for a robust globally
distributed blockchain with very fast transaction confirmation times, and, as
bandwidth, storage, and parallel compute capacity increases, we will be able to
support more validators in the future.</p>
<p>On genesis day, the maximum number of validators will be set to 100, and this
number will increase at a rate of 13% for 10 years, and settle at 300
validators.</p>
<pre><code>Year 0: 100
Year 1: 113
Year 2: 127
Year 3: 144
Year 4: 163
Year 5: 184
Year 6: 208
Year 7: 235
Year 8: 265
Year 9: 300
Year 10: 300
...
</code></pre>
<h3><a id="user-content-becoming-a-validator-after-genesis-day" class="anchor" aria-hidden="true" href="#becoming-a-validator-after-genesis-day"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Becoming a Validator After Genesis Day</h3>
<p>Atom holders who are not already can become validators by signing and
submitting a <code>BondTx</code> transaction.  The amount of atoms provided as collateral
must be nonzero.  Anyone can become a validator at any time, except when the
size of the current validator set is greater than the maximum number of
validators allowed.  In that case, the transaction is only valid if the amount
of atoms is greater than the amount of effective atoms held by the smallest
validator, where effective atoms include delegated atoms.  When a new validator
replaces an existing validator in such a way, the existing validator becomes
inactive and all the atoms and delegated atoms enter the unbonding state.</p>
<h3><a id="user-content-penalties-for-validators" class="anchor" aria-hidden="true" href="#penalties-for-validators"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Penalties for Validators</h3>
<p>There must be some penalty imposed on the validators for any intentional
or unintentional deviation from the sanctioned protocol. Some evidence is
immediately admissible, such as a double-sign at the same height and round, or a
violation of "prevote-the-lock" (a rule of the Tendermint consensus protocol).
Such evidence will result in the validator losing its good standing and its
bonded atoms as well its proportionate share of tokens in the reserve pool --
collectively called its "stake" -- will get slashed.</p>
<p>Sometimes, validators will not be available, either due to regional network
disruptions, power failure, or other reasons.  If, at any point in the past
<code>ValidatorTimeoutWindow</code> blocks, a validator's commit vote is not included in
the blockchain more than <code>ValidatorTimeoutMaxAbsent</code> times, that validator will
become inactive, and lose <code>ValidatorTimeoutPenalty</code> (DEFAULT 1%) of its stake.</p>
<p>Some "malicious" behavior does not produce obviously discernible evidence on the
blockchain. In these cases, the validators can coordinate out of band to force
the timeout of these malicious validators, if there is a supermajority
consensus.</p>
<p>In situations where the Cosmos Hub halts due to a ≥⅓ coalition of voting power
going offline, or in situations where a ≥⅓ coalition of voting power censor
evidence of malicious behavior from entering the blockchain, the hub must
recover with a hard-fork reorg-proposal.  (Link to "Forks and Censorship
Attacks").</p>
<h3><a id="user-content-transaction-fees" class="anchor" aria-hidden="true" href="#transaction-fees"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Transaction Fees</h3>
<p>Cosmos Hub validators can accept any token type or combination of types as fees
for processing a transaction.  Each validator can subjectively set whatever
exchange rate it wants, and choose whatever transactions it wants, as long as
the <code>BlockGasLimit</code> is not exceeded.  The collected fees, minus any taxes
specified below, are redistributed to the bonded stakeholders in proportion to
their bonded atoms, every <code>ValidatorPayoutPeriod</code> (DEFAULT 1 hour).</p>
<p>Of the collected transaction fees, <code>ReserveTax</code> (DEFAULT 2%) will go toward the
reserve pool to increase the reserve pool and increase the security and value of
the Cosmos network. These funds can also be distributed in accordance with the
decisions made by the governance system.</p>
<p>Atom holders who delegate their voting power to other validators pay a
commission to the delegated validator.  The commission can be set by each
validator.</p>
<h3><a id="user-content-incentivizing-hackers" class="anchor" aria-hidden="true" href="#incentivizing-hackers"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Incentivizing Hackers</h3>
<p>The security of the Cosmos Hub is a function of the security of the underlying
validators and the choice of delegation by delegators.  In order to encourage
the discovery and early reporting of found vulnerabilities, the Cosmos Hub
encourages hackers to publish successful exploits via a <code>ReportHackTx</code>
transaction that says, "This validator got hacked.  Please send
bounty to this address".  Upon such an exploit, the validator and delegators
will become inactive, <code>HackPunishmentRatio</code> (default 5%) of everyone's atoms
will get slashed, and <code>HackRewardRatio</code> (default 5%) of everyone's atoms will
get rewarded to the hacker's bounty address.  The validator must recover the
remaining atoms by using their backup key.</p>
<p>In order to prevent this feature from being abused to transfer unvested atoms,
the portion of vested vs unvested atoms of validators and delegators before and
after the <code>ReportHackTx</code> will remain the same, and the hacker bounty will
include some unvested atoms, if any.</p>
<h3><a id="user-content-governance-specification" class="anchor" aria-hidden="true" href="#governance-specification"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Governance Specification</h3>
<p>The Cosmos Hub is operated by a distributed organization that requires a well-defined
governance mechanism in order to coordinate various changes to the blockchain,
such as the variable parameters of the system, as well as software upgrades and
constitutional amendments.</p>
<p>All validators are responsible for voting on all proposals.  Failing to vote on
a proposal in a timely manner will result in the validator being deactivated
automatically for a period of time called the <code>AbsenteeismPenaltyPeriod</code>
(DEFAULT 1 week).</p>
<p>Delegators automatically inherit the vote of the delegated validator.  This vote
may be overridden manually.  Unbonded atoms get no vote.</p>
<p>Each proposal requires a deposit of <code>MinimumProposalDeposit</code> tokens, which may
be a combination of one or more tokens including atoms.  For each proposal, the
voters may vote to take the deposit. If more than half of the voters choose to
take the deposit (e.g. because the proposal was spam), the deposit goes to the
reserve pool, except any atoms which are burned.</p>
<p>For each proposal, voters may vote with the following options:</p>
<ul>
<li>Yea</li>
<li>YeaWithForce</li>
<li>Nay</li>
<li>NayWithForce</li>
<li>Abstain</li>
</ul>
<p>A strict majority of Yea or YeaWithForce votes (or Nay or NayWithForce votes) is
required for the proposal to be decided as passed (or decided as failed), but
1/3+ can veto the majority decision by voting "with force".  When a strict
majority is vetoed, everyone gets punished by losing <code>VetoPenaltyFeeBlocks</code>
(DEFAULT 1 day's worth of blocks) worth of fees (except taxes which will not be
affected), and the party that vetoed the majority decision will be additionally
punished by losing <code>VetoPenaltyAtoms</code> (DEFAULT 0.1%) of its atoms.</p>
<h3><a id="user-content-parameter-change-proposal" class="anchor" aria-hidden="true" href="#parameter-change-proposal"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Parameter Change Proposal</h3>
<p>Any of the parameters defined here can be changed with the passing of a
<code>ParameterChangeProposal</code>.</p>
<h3><a id="user-content-bounty-proposal" class="anchor" aria-hidden="true" href="#bounty-proposal"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Bounty Proposal</h3>
<p>Atoms can be inflated and reserve pool funds spent with the passing of a <code>BountyProposal</code>.</p>
<h3><a id="user-content-text-proposal" class="anchor" aria-hidden="true" href="#text-proposal"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Text Proposal</h3>
<p>All other proposals, such as a proposal to upgrade the protocol, will be
coordinated via the generic <code>TextProposal</code>.</p>
<h2><a id="user-content-roadmap" class="anchor" aria-hidden="true" href="#roadmap"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Roadmap</h2>
<p>See <a href="https://github.com/cosmos/cosmos/blob/master/PLAN.md">the Plan</a>.</p>
<h2><a id="user-content-related-work" class="anchor" aria-hidden="true" href="#related-work"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Related Work</h2>
<p>There have been many innovations in blockchain consensus and scalability in the
past couple of years.  This section provides a brief survey of a select number
of important ones.</p>
<h3><a id="user-content-consensus-systems" class="anchor" aria-hidden="true" href="#consensus-systems"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Consensus Systems</h3>
<h4><a id="user-content-classic-byzantine-fault-tolerance" class="anchor" aria-hidden="true" href="#classic-byzantine-fault-tolerance"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Classic Byzantine Fault Tolerance</h4>
<p>Consensus in the presence of malicious participants is a problem dating back to
the early 1980s, when Leslie Lamport coined the phrase "Byzantine fault" to
refer to arbitrary process behavior that deviates from the intended behavior,
in contrast to a "crash fault", wherein a process simply crashes. Early
solutions were discovered for synchronous networks where there is an upper
bound on message latency, though practical use was limited to highly controlled
environments such as airplane controllers and datacenters synchronized via
atomic clocks.  It was not until the late 90s that Practical Byzantine Fault
Tolerance (PBFT) <a href="http://pmg.csail.mit.edu/papers/osdi99.pdf" rel="nofollow">[11]</a> was introduced as an efficient partially
synchronous consensus algorithm able to tolerate up to ⅓ of processes behaving
arbitrarily.  PBFT became the standard algorithm, spawning many variations,
including most recently one created by IBM as part of their contribution to
Hyperledger.</p>
<p>The main benefit of Tendermint consensus over PBFT is that Tendermint has an
improved and simplified underlying structure, some of which is a result of
embracing the blockchain paradigm.  Tendermint blocks must commit in order,
which obviates the complexity and communication overhead associated with PBFT's
view-changes.  In Cosmos and many cryptocurrencies, there is no need to allow
for block <em>N+i</em> where <em>i &gt;= 1</em> to commit, when block <em>N</em>
itself hasn't yet committed. If bandwidth is the reason why block <em>N</em>
hasn't committed in a Cosmos zone, then it doesn't help to use bandwidth sharing
votes for blocks <em>N+i</em>. If a network partition or offline nodes is the
reason why block <em>N</em> hasn't committed, then <em>N+i</em> won't commit
anyway.</p>
<p>In addition, the batching of transactions into blocks allows for regular
Merkle-hashing of the application state, rather than periodic digests as with
PBFT's checkpointing scheme.  This allows for faster provable transaction
commits for light-clients and faster inter-blockchain communication.</p>
<p>Tendermint Core also includes many optimizations and features that go above and
beyond what is specified in PBFT.  For example, the blocks proposed by
validators are split into parts, Merkle-ized, and gossipped in such a way that
improves broadcasting performance (see LibSwift <a href="http://www.ds.ewi.tudelft.nl/fileadmin/pds/papers/PerformanceAnalysisOfLibswift.pdf" rel="nofollow">[19]</a> for inspiration).
Also, Tendermint Core doesn't make any assumption about point-to-point
connectivity, and functions for as long as the P2P network is weakly connected.</p>
<h4><a id="user-content-bitshares-delegated-stake" class="anchor" aria-hidden="true" href="#bitshares-delegated-stake"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>BitShares delegated stake</h4>
<p>While not the first to deploy proof-of-stake (PoS), BitShares1.0 <a href="https://bitshares.org/technology/delegated-proof-of-stake-consensus/" rel="nofollow">[12]</a>
contributed considerably to research and adoption of PoS blockchains,
particularly those known as "delegated" PoS.  In BitShares, stake holders elect
"witnesses", responsible for ordering and committing transactions, and
"delegates", responsible for coordinating software updates and parameter
changes.  BitShares2.0 aims to achieve high performance (100k tx/s, 1s latency)
in ideal conditions, with each block signed by a single signer, and transaction
finality taking quite a bit longer than the block interval.  A canonical
specification is still in development.  Stakeholders can remove or replace
misbehaving witnesses on a daily basis, but there is no significant collateral
of witnesses or delegators in the likeness of Tendermint PoS that get slashed
in the case of a successful double-spend attack.</p>
<h4><a id="user-content-stellar" class="anchor" aria-hidden="true" href="#stellar"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Stellar</h4>
<p>Building on an approach pioneered by Ripple, Stellar <a href="https://www.stellar.org/papers/stellar-consensus-protocol.pdf" rel="nofollow">[13]</a> refined a
model of Federated Byzantine Agreement wherein the processes participating in
consensus do not constitute a fixed and globally known set.  Rather, each
process node curates one or more "quorum slices", each constituting a set of
trusted processes. A "quorum" in Stellar is defined to be a set of nodes that
contain at least one quorum slice for each node in the set, such that agreement
can be reached.</p>
<p>The security of the Stellar mechanism relies on the assumption that the
intersection of <em>any</em> two quorums is non-empty, while the availability of a node
requires at least one of its quorum slices to consist entirely of correct nodes,
creating a trade-off between using large or small quorum-slices that may be
difficult to balance without imposing significant assumptions about trust.
Ultimately, nodes must somehow choose adequate quorum slices for there to be
sufficient fault-tolerance (or any "intact nodes" at all, of which much of the
results of the paper depend on), and the only provided strategy for ensuring
such a configuration is hierarchical and similar to the Border Gateway Protocol
(BGP), used by top-tier ISPs on the internet to establish global routing tables,
and by that used by browsers to manage TLS certificates; both notorious for
their insecurity.</p>
<p>The criticism in the Stellar paper of the Tendermint-based proof-of-stake
systems is mitigated by the token strategy described here, wherein a new type of
token called the <em>atom</em> is issued that represent claims to future portions of
fees and rewards. The advantage of Tendermint-based proof-of-stake, then, is its
relative simplicity, while still providing sufficient and provable security
guarantees.</p>
<h4><a id="user-content-bitcoinng" class="anchor" aria-hidden="true" href="#bitcoinng"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>BitcoinNG</h4>
<p>BitcoinNG is a proposed improvement to Bitcoin that would allow for forms of
vertical scalability, such as increasing the block size, without the negative
economic consequences typically associated with such a change, such as the
disproportionately large impact on small miners.  This improvement is achieved
by separating leader election from transaction broadcast: leaders are first
elected by proof-of-work in "key-blocks", and then able to broadcast
transactions to be committed until a new key-block is found. This reduces the
bandwidth requirements necessary to win the PoW race, allowing small miners to
more fairly compete, and allowing transactions to be committed more regularly by
the last miner to find a key-block.</p>
<h4><a id="user-content-casper" class="anchor" aria-hidden="true" href="#casper"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Casper</h4>
<p>Casper <a href="https://blog.ethereum.org/2015/08/01/introducing-casper-friendly-ghost/" rel="nofollow">[16]</a> is a proposed proof-of-stake consensus algorithm for
Ethereum.  Its prime mode of operation is "consensus-by-bet".  By letting
validators iteratively bet on which block they believe will become committed
into the blockchain based on the other bets that they have seen so far,
finality can be achieved eventually.
<a href="https://blog.ethereum.org/2015/12/28/understanding-serenity-part-2-casper/" rel="nofollow">link</a>.
This is an active area of research by the Casper team.  The challenge is in
constructing a betting mechanism that can be proven to be an evolutionarily
stable strategy.  The main benefit of Casper as compared to Tendermint may be in
offering "availability over consistency" -- consensus does not require a &gt;⅔
quorum of voting power -- perhaps at the cost of commit speed or
implementation complexity.</p>
<h3><a id="user-content-horizontal-scaling" class="anchor" aria-hidden="true" href="#horizontal-scaling"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Horizontal Scaling</h3>
<h4><a id="user-content-interledger-protocol" class="anchor" aria-hidden="true" href="#interledger-protocol"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Interledger Protocol</h4>
<p>The Interledger Protocol <a href="https://interledger.org/rfcs/0001-interledger-architecture/" rel="nofollow">[14]</a> is not strictly a scalability solution.
It provides an ad hoc interoperation between different ledger systems through a
loosely coupled bilateral relationship network.  Like the Lightning Network,
the purpose of ILP is to facilitate payments, but it specifically focuses on
payments across disparate ledger types, and extends the atomic transaction
mechanism to include not only hash-locks, but also a quorum of notaries (called
the Atomic Transport Protocol).  The latter mechanism for enforcing atomicity
in inter-ledger transactions is similar to Tendermint's light-client SPV
mechanism, so an illustration of the distinction between ILP and Cosmos/IBC is
warranted, and provided below.</p>
<ol>
<li>
<p>The notaries of a connector in ILP do not support membership changes, and
do not allow for flexible weighting between notaries.  On the other hand,
IBC is designed specifically for blockchains, where validators can have
different weights, and where membership can change over the course of the
blockchain.</p>
</li>
<li>
<p>As in the Lightning Network, the receiver of payment in ILP must be online to
send a confirmation back to the sender.  In a token transfer over IBC, the
validator-set of the receiver's blockchain is responsible for providing
confirmation, not the receiving user.</p>
</li>
<li>
<p>The most striking difference is that ILP's connectors are not responsible or
keeping authoritative state about payments, whereas in Cosmos, the validators
of a hub are the authority of the state of IBC token transfers as well as the
authority of the amount of tokens held by each zone (but not the amount of
tokens held by each account within a zone).  This is the fundamental innovation
that allows for secure asymmetric transfer of tokens from zone to zone; the
analog to ILP's connector in Cosmos is a persistent and maximally secure
blockchain ledger, the Cosmos Hub.</p>
</li>
<li>
<p>The inter-ledger payments in ILP need to be backed by an exchange orderbook,
as there is no asymmetric transfer of coins from one ledger to another, only
the transfer of value or market equivalents.</p>
</li>
</ol>
<h4><a id="user-content-sidechains" class="anchor" aria-hidden="true" href="#sidechains"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Sidechains</h4>
<p>Sidechains <a href="https://blockstream.com/sidechains.pdf" rel="nofollow">[15]</a> are a proposed mechanism for scaling the Bitcoin
network via alternative blockchains that are "two-way pegged" to the Bitcoin
blockchain. (Two-way pegging is equivalent to bridging. In Cosmos we say
"bridging" to distinguish from market-pegging).  Sidechains allow bitcoins to
effectively move from the Bitcoin blockchain to the sidechain and back, and
allow for experimentation in new features on the sidechain.  As in the Cosmos
Hub, the sidechain and Bitcoin serve as light-clients of each other, using SPV
proofs to determine when coins should be transferred to the sidechain and back.
Of course, since Bitcoin uses proof-of-work, sidechains centered around Bitcoin
suffer from the many problems and risks of proof-of-work as a consensus
mechanism.  Furthermore, this is a Bitcoin-maximalist solution that doesn't
natively support a variety of tokens and inter-zone network topology as Cosmos
does. That said, the core mechanism of the two-way peg is in principle the same
as that employed by the Cosmos network.</p>
<h4><a id="user-content-ethereum-scalability-efforts" class="anchor" aria-hidden="true" href="#ethereum-scalability-efforts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Ethereum Scalability Efforts</h4>
<p>Ethereum is currently researching a number of different strategies to shard the
state of the Ethereum blockchain to address scalability needs. These efforts
have the goal of maintaining the abstraction layer offered by the current
Ethereum Virtual Machine across the shared state space. Multiple research
efforts are underway at this time. <a href="https://github.com/ethereum/EIPs/issues/53">[18]</a><a href="http://vitalik.ca/files/mauve_paper.html" rel="nofollow">[22]</a></p>
<h5><a id="user-content-cosmos-vs-ethereum-20-mauve" class="anchor" aria-hidden="true" href="#cosmos-vs-ethereum-20-mauve"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Cosmos vs Ethereum 2.0 Mauve</h5>
<p>Cosmos and Ethereum 2.0 Mauve <a href="http://vitalik.ca/files/mauve_paper.html" rel="nofollow">[22]</a> have different design goals.</p>
<ul>
<li>Cosmos is specifically about tokens.  Mauve is about scaling general computation.</li>
<li>Cosmos is not bound to the EVM, so even different VMs can interoperate.</li>
<li>Cosmos lets the zone creator determine who validates the zone.</li>
<li>Anyone can start a new zone in Cosmos (unless governance decides otherwise).</li>
<li>The hub isolates zone failures so global token invariants are preserved.</li>
</ul>
<h3><a id="user-content-general-scaling" class="anchor" aria-hidden="true" href="#general-scaling"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>General Scaling</h3>
<h4><a id="user-content-lightning-network" class="anchor" aria-hidden="true" href="#lightning-network"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Lightning Network</h4>
<p>The Lightning Network is a proposed token transfer network operating at a layer
above the Bitcoin blockchain (and other public blockchains), enabling improvement of many
orders of magnitude in transaction throughput by moving the majority
of transactions outside of the consensus ledger into so-called "payment
channels". This is made possible by on-chain cryptocurrency scripts, which
enable parties to enter into bilateral stateful contracts where the state can
be updated by sharing digital signatures, and contracts can be closed by finally
publishing evidence onto the blockchain, a mechanism first popularized by
cross-chain atomic swaps.  By opening payment channels with many parties,
participants in the Lightning Network can become focal points for routing the
payments of others, leading to a fully connected payment channel network, at the
cost of capital being tied up on payment channels.</p>
<p>While the Lightning Network can also easily extend across multiple independent
blockchains to allow for the transfer of <em>value</em> via an exchange market, it
cannot be used to asymmetrically transfer <em>tokens</em> from one blockchain to
another.  The main benefit of the Cosmos network described here is to enable
such direct token transfers.  That said, we expect payment channels and the
Lightning Network to become widely adopted along with our token transfer
mechanism, for cost-saving and privacy reasons.</p>
<h4><a id="user-content-segregated-witness" class="anchor" aria-hidden="true" href="#segregated-witness"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Segregated Witness</h4>
<p>Segregated Witness is a Bitcoin improvement proposal
<a href="https://github.com/bitcoin/bips/blob/master/bip-0141.mediawiki">link</a> that aims
to increase the per-block transaction throughput 2X or 3X, while simultaneously
making block syncing faster for new nodes.  The brilliance of this solution is
in how it works within the limitations of Bitcoin's current protocol and allows
for a soft-fork upgrade (i.e. clients with older versions of the software will
continue to function after the upgrade).  Tendermint, being a new protocol, has no
design restrictions, so it has a different scaling priorities.  Primarily,
Tendermint uses a BFT round-robin algorithm based on cryptographic signatures
instead of mining, which trivially allows horizontal scaling through multiple
parallel blockchains, while regular, more frequent block commits allow for
vertical scaling as well.</p>
<hr>
<h2><a id="user-content-appendix" class="anchor" aria-hidden="true" href="#appendix"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Appendix</h2>
<h3><a id="user-content-fork-accountability" class="anchor" aria-hidden="true" href="#fork-accountability"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Fork Accountability</h3>
<p>A well designed consensus protocol should provide some guarantees in the event that the tolerance
capacity is exceeded and the consensus fails.  This is especially necessary in
economic systems, where Byzantine behaviour can have substantial financial
reward.  The most important such guarantee is a form of <em>fork-accountability</em>,
where the processes that caused the consensus to fail (ie.  caused clients of
the protocol to accept different values - a fork) can be identified and punished
according to the rules of the protocol, or, possibly, the legal system.  When
the legal system is unreliable or excessively expensive to invoke, validators can be forced to make security
deposits in order to participate, and those deposits can be revoked, or slashed,
when malicious behaviour is detected <a href="https://blog.ethereum.org/2014/01/15/slasher-a-punitive-proof-of-stake-algorithm/" rel="nofollow">[10]</a>.</p>
<p>Note this is unlike Bitcoin, where forking is a regular occurrence due to
network asynchrony and the probabilistic nature of finding partial hash
collisions.  Since in many cases a malicious fork is indistinguishable from a
fork due to asynchrony, Bitcoin cannot reliably implement fork-accountability,
other than the implicit opportunity cost paid by miners for mining an orphaned
block.</p>
<h3><a id="user-content-tendermint-consensus" class="anchor" aria-hidden="true" href="#tendermint-consensus"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Tendermint Consensus</h3>
<p>We call the voting stages <em>PreVote</em> and <em>PreCommit</em>. A vote can be for a
particular block or for <em>Nil</em>.  We call a collection of &gt;⅔ PreVotes for a single
block in the same round a <em>Polka</em>, and a collection of &gt;⅔ PreCommits for a
single block in the same round a <em>Commit</em>.  If &gt;⅔ PreCommit for Nil in the same
round, they move to the next round.</p>
<p>Note that strict determinism in the protocol incurs a weak synchrony assumption
as faulty leaders must be detected and skipped.  Thus, validators wait some
amount of time, <em>TimeoutPropose</em>, before they Prevote Nil, and the value of
TimeoutPropose increases with each round.  Progression through the rest of a
round is fully asynchronous, in that progress is only made once a validator hears
from &gt;⅔ of the network.  In practice, it would take an extremely strong
adversary to indefinitely thwart the weak synchrony assumption (causing the
consensus to fail to ever commit a block), and doing so can be made even more
difficult by using randomized values of TimeoutPropose on each validator.</p>
<p>An additional set of constraints, or Locking Rules, ensure that the network will
eventually commit just one block at each height. Any malicious attempt to cause
more than one block to be committed at a given height can be identified.  First,
a PreCommit for a block must come with justification, in the form of a Polka for
that block. If the validator has already PreCommit a block at round
<em>R_1</em>, we say they are <em>locked</em> on that block, and the Polka used to
justify the new PreCommit at round <em>R_2</em> must come in a round
<em>R_polka</em> where <em>R_1 &lt; R_polka &lt;= R_2</em>.  Second, validators
must Propose and/or PreVote the block they are locked on.  Together, these
conditions ensure that a validator does not PreCommit without sufficient
evidence as justification, and that validators which have already PreCommit
cannot contribute to evidence to PreCommit something else.  This ensures both
safety and liveness of the consensus algorithm.</p>
<p>The full details of the protocol are described
<a href="https://github.com/tendermint/tendermint/wiki/Byzantine-Consensus-Algorithm">here</a>.</p>
<h3><a id="user-content-tendermint-light-clients" class="anchor" aria-hidden="true" href="#tendermint-light-clients"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Tendermint Light Clients</h3>
<p>The need to sync all block headers is eliminated in Tendermint-PoS as the
existence of an alternative chain (a fork) means ≥⅓ of bonded stake can be
slashed.  Of course, since slashing requires that <em>someone</em> share evidence of a
fork, light clients should store any block-hash commits that it sees.
Additionally, light clients could periodically stay synced with changes to the
validator set, in order to avoid <a href="#preventing-long-range-attacks">long range
attacks</a> (but other solutions are possible).</p>
<p>In spirit similar to Ethereum, Tendermint enables applications to embed a
global Merkle root hash in each block, allowing easily verifiable state queries
for things like account balances, the value stored in a contract, or the
existence of an unspent transaction output, depending on the nature of the
application.</p>
<h3><a id="user-content-preventing-long-range-attacks" class="anchor" aria-hidden="true" href="#preventing-long-range-attacks"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Preventing Long Range Attacks</h3>
<p>Assuming a sufficiently resilient collection of broadcast networks and a static
validator set, any fork in the blockchain can be detected and the deposits of
the offending validators slashed.  This innovation, first suggested by Vitalik
Buterin in early 2014, solves the nothing-at-stake problem of other
proof-of-stake cryptocurrencies (see <a href="#related-work">Related Work</a>). However,
since validator sets must be able to change, over a long range of time the
original validators may all become unbonded, and hence would be free to create a
new chain from the genesis block, incurring no cost as they no longer have
deposits locked up.  This attack came to be known as the Long Range Attack (LRA),
in contrast to a Short Range Attack, where validators who are currently bonded
cause a fork and are hence punishable (assuming a fork-accountable BFT algorithm
like Tendermint consensus). Long Range Attacks are often thought to be a
critical blow to proof-of-stake.</p>
<p>Fortunately, the LRA can be mitigated as follows.  First, for a validator to
unbond (thereby recovering their collateral deposit and no longer earning fees
to participate in the consensus), the deposit must be made untransferable for an
amount of time known as the "unbonding period", which may be on the order of
weeks or months.  Second, for a light client to be secure, the first time it
connects to the network it must verify a recent block-hash against a trusted
source, or preferably multiple sources.  This condition is sometimes referred to
as "weak subjectivity".  Finally, to remain secure, it must sync up with the
latest validator set at least as frequently as the length of the unbonding
period. This ensures that the light client knows about changes to the validator
set before a validator has its capital unbonded and thus no longer at stake,
which would allow it to deceive the client by carrying out a long range attack
by creating new blocks beginning back at a height where it was bonded (assuming
it has control of sufficiently many of the early private keys).</p>
<p>Note that overcoming the LRA in this way requires an overhaul of the original
security model of proof-of-work. In PoW, it is assumed that a light client can
sync to the current height from the trusted genesis block at any time simply by
processing the proof-of-work in every block header.  To overcome the LRA,
however, we require that a light client come online with some regularity to
track changes in the validator set, and that the first time they come online
they must be particularly careful to authenticate what they hear from the
network against trusted sources. Of course, this latter requirement is similar
to that of Bitcoin, where the protocol and software must also be obtained from a
trusted source.</p>
<p>The above method for preventing LRA is well suited for validators and full nodes
of a Tendermint-powered blockchain because these nodes are meant to remain
connected to the network.  The method is also suitable for light clients that
can be expected to sync with the network frequently.  However, for light clients
that are not expected to have frequent access to the internet or the blockchain
network, yet another solution can be used to overcome the LRA.  Non-validator
token holders can post their tokens as collateral with a very long unbonding
period (e.g. much longer than the unbonding period for validators) and serve
light clients with a secondary method of attesting to the validity of current
and past block-hashes. While these tokens do not count toward the security of
the blockchain's consensus, they nevertheless can provide strong guarantees for
light clients.  If historical block-hash querying were supported in Ethereum,
anyone could bond their tokens in a specially designed smart contract and
provide attestation services for pay, effectively creating a market for
light-client LRA security.</p>
<h3><a id="user-content-overcoming-forks-and-censorship-attacks" class="anchor" aria-hidden="true" href="#overcoming-forks-and-censorship-attacks"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Overcoming Forks and Censorship Attacks</h3>
<p>Due to the definition of a block commit, any ≥⅓ coalition of voting power can
halt the blockchain by going offline or not broadcasting their votes. Such a
coalition can also censor particular transactions by rejecting blocks that
include these transactions, though this would result in a significant proportion
of block proposals to be rejected, which would slow down the rate of block
commits of the blockchain, reducing its utility and value. The malicious
coalition might also broadcast votes in a trickle so as to grind blockchain
block commits to a near halt, or engage in any combination of these attacks.
Finally, it can cause the blockchain to fork, by double-signing or violating the
locking rules.</p>
<p>If a globally active adversary were also involved, it could partition the network in
such a way that it may appear that the wrong subset of validators were
responsible for the slowdown. This is not just a limitation of Tendermint, but
rather a limitation of all consensus protocols whose network is potentially
controlled by an active adversary.</p>
<p>For these types of attacks, a subset of the validators should coordinate through
external means to sign a reorg-proposal that chooses a fork (and any evidence
thereof) and the initial subset of validators with their signatures. Validators
who sign such a reorg-proposal forego their collateral on all other forks.
Clients should verify the signatures on the reorg-proposal, verify any evidence,
and make a judgement or prompt the end-user for a decision.  For example, a
phone wallet app may prompt the user with a security warning, while a
refrigerator may accept any reorg-proposal signed by +½ of the original
validators by voting power.</p>
<p>No non-synchronous Byzantine fault-tolerant algorithm can come to consensus when
≥⅓ of voting power are dishonest, yet a fork assumes that ≥⅓ of voting power
have already been dishonest by double-signing or lock-changing without
justification.  So, signing the reorg-proposal is a coordination problem that
cannot be solved by any non-synchronous protocol (i.e. automatically, and
without making assumptions about the reliability of the underlying network).
For now, we leave the problem of reorg-proposal coordination to human
coordination via social consensus on internet media.  Validators must take care
to ensure that there are no remaining network partitions prior to signing a
reorg-proposal, to avoid situations where two conflicting reorg-proposals are
signed.</p>
<p>Assuming that the external coordination medium and protocol is robust, it
follows that forks are less of a concern than censorship attacks.</p>
<p>In addition to forks and censorship, which require ≥⅓ Byzantine voting power, a
coalition of &gt;⅔ voting power may commit arbitrary, invalid state.  This is
characteristic of any (BFT) consensus system. Unlike double-signing, which
creates forks with easily verifiable evidence, detecting commitment of an
invalid state requires non-validating peers to verify whole blocks, which
implies that they keep a local copy of the state and execute each transaction,
computing the state root independently for themselves.  Once detected, the only
way to handle such a failure is via social consensus.  For instance, in
situations where Bitcoin has failed, whether forking due to software bugs (as in
March 2013), or committing invalid state due to Byzantine behavior of miners (as
in July 2015), the well connected community of businesses, developers, miners,
and other organizations established a social consensus as to what manual actions
were required by participants to heal the network.  Furthermore, since
validators of a Tendermint blockchain may be expected to be identifiable,
commitment of an invalid state may even be punishable by law or some external
jurisprudence, if desired.</p>
<h3><a id="user-content-abci-specification" class="anchor" aria-hidden="true" href="#abci-specification"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>ABCI Specification</h3>
<p>ABCI consists of 3 primary message types that get delivered from the core to the
application. The application replies with corresponding response messages.</p>
<p>The <code>AppendTx</code> message is the work horse of the application. Each transaction in
the blockchain is delivered with this message. The application needs to validate
each transactions received with the AppendTx message against the current state,
application protocol, and the cryptographic credentials of the transaction. A
validated transaction then needs to update the application state — by binding a
value into a key values store, or by updating the UTXO database.</p>
<p>The <code>CheckTx</code> message is similar to AppendTx, but it’s only for validating
transactions. Tendermint Core’s mempool first checks the validity of a
transaction with CheckTx, and only relays valid transactions to its peers.
Applications may check an incrementing nonce in the transaction and return an
error upon CheckTx if the nonce is old.</p>
<p>The <code>Commit</code> message is used to compute a cryptographic commitment to the
current application state, to be placed into the next block header. This has
some handy properties. Inconsistencies in updating that state will now appear as
blockchain forks which catches a whole class of programming errors. This also
simplifies the development of secure lightweight clients, as Merkle-hash proofs
can be verified by checking against the block-hash, and the block-hash is signed
by a quorum of validators (by voting power).</p>
<p>Additional ABCI messages allow the application to keep track of and change the
validator set, and for the application to receive the block information, such as
the height and the commit votes.</p>
<p>ABCI requests/responses are simple Protobuf messages.  Check out the <a href="https://github.com/tendermint/abci/blob/master/types/types.proto">schema
file</a>.</p>
<h5><a id="user-content-appendtx" class="anchor" aria-hidden="true" href="#appendtx"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>AppendTx</h5>
<ul>
<li><strong>Arguments</strong>:
<ul>
<li><code>Data ([]byte)</code>: The request transaction bytes</li>
</ul>
</li>
<li><strong>Returns</strong>:
<ul>
<li><code>Code (uint32)</code>: Response code</li>
<li><code>Data ([]byte)</code>: Result bytes, if any</li>
<li><code>Log (string)</code>: Debug or error message</li>
</ul>
</li>
<li><strong>Usage</strong>:<br>
Append and run a transaction.  If the transaction is valid, returns
CodeType.OK</li>
</ul>
<h5><a id="user-content-checktx" class="anchor" aria-hidden="true" href="#checktx"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>CheckTx</h5>
<ul>
<li><strong>Arguments</strong>:
<ul>
<li><code>Data ([]byte)</code>: The request transaction bytes</li>
</ul>
</li>
<li><strong>Returns</strong>:
<ul>
<li><code>Code (uint32)</code>: Response code</li>
<li><code>Data ([]byte)</code>: Result bytes, if any</li>
<li><code>Log (string)</code>: Debug or error message</li>
</ul>
</li>
<li><strong>Usage</strong>:<br>
Validate a transaction.  This message should not mutate the state.
Transactions are first run through CheckTx before broadcast to peers in the
mempool layer.
You can make CheckTx semi-stateful and clear the state upon <code>Commit</code> or
<code>BeginBlock</code>,
to allow for dependent sequences of transactions in the same block.</li>
</ul>
<h5><a id="user-content-commit" class="anchor" aria-hidden="true" href="#commit"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Commit</h5>
<ul>
<li><strong>Returns</strong>:
<ul>
<li><code>Data ([]byte)</code>: The Merkle root hash</li>
<li><code>Log (string)</code>: Debug or error message</li>
</ul>
</li>
<li><strong>Usage</strong>:<br>
Return a Merkle root hash of the application state.</li>
</ul>
<h5><a id="user-content-query" class="anchor" aria-hidden="true" href="#query"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Query</h5>
<ul>
<li><strong>Arguments</strong>:
<ul>
<li><code>Data ([]byte)</code>: The query request bytes</li>
</ul>
</li>
<li><strong>Returns</strong>:
<ul>
<li><code>Code (uint32)</code>: Response code</li>
<li><code>Data ([]byte)</code>: The query response bytes</li>
<li><code>Log (string)</code>: Debug or error message</li>
</ul>
</li>
</ul>
<h5><a id="user-content-flush" class="anchor" aria-hidden="true" href="#flush"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Flush</h5>
<ul>
<li><strong>Usage</strong>:<br>
Flush the response queue.  Applications that implement <code>types.Application</code>
need not implement this message -- it's handled by the project.</li>
</ul>
<h5><a id="user-content-info" class="anchor" aria-hidden="true" href="#info"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Info</h5>
<ul>
<li><strong>Returns</strong>:
<ul>
<li><code>Data ([]byte)</code>: The info bytes</li>
</ul>
</li>
<li><strong>Usage</strong>:<br>
Return information about the application state.  Application specific.</li>
</ul>
<h5><a id="user-content-setoption" class="anchor" aria-hidden="true" href="#setoption"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>SetOption</h5>
<ul>
<li><strong>Arguments</strong>:
<ul>
<li><code>Key (string)</code>: Key to set</li>
<li><code>Value (string)</code>: Value to set for key</li>
</ul>
</li>
<li><strong>Returns</strong>:
<ul>
<li><code>Log (string)</code>: Debug or error message</li>
</ul>
</li>
<li><strong>Usage</strong>:<br>
Set application options.  E.g. Key="mode", Value="mempool" for a mempool
connection, or Key="mode", Value="consensus" for a consensus connection.
Other options are application specific.</li>
</ul>
<h5><a id="user-content-initchain" class="anchor" aria-hidden="true" href="#initchain"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>InitChain</h5>
<ul>
<li><strong>Arguments</strong>:
<ul>
<li><code>Validators ([]Validator)</code>: Initial genesis-validators</li>
</ul>
</li>
<li><strong>Usage</strong>:<br>
Called once upon genesis</li>
</ul>
<h5><a id="user-content-beginblock" class="anchor" aria-hidden="true" href="#beginblock"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>BeginBlock</h5>
<ul>
<li><strong>Arguments</strong>:
<ul>
<li><code>Height (uint64)</code>: The block height that is starting</li>
</ul>
</li>
<li><strong>Usage</strong>:<br>
Signals the beginning of a new block. Called prior to any AppendTxs.</li>
</ul>
<h5><a id="user-content-endblock" class="anchor" aria-hidden="true" href="#endblock"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>EndBlock</h5>
<ul>
<li><strong>Arguments</strong>:
<ul>
<li><code>Height (uint64)</code>: The block height that ended</li>
</ul>
</li>
<li><strong>Returns</strong>:
<ul>
<li><code>Validators ([]Validator)</code>: Changed validators with new voting powers (0
to remove)</li>
</ul>
</li>
<li><strong>Usage</strong>:<br>
Signals the end of a block.  Called prior to each Commit after all
transactions</li>
</ul>
<p>See <a href="https://github.com/tendermint/abci#message-types">the ABCI repository</a> for more details.</p>
<h3><a id="user-content-ibc-packet-delivery-acknowledgement" class="anchor" aria-hidden="true" href="#ibc-packet-delivery-acknowledgement"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>IBC Packet Delivery Acknowledgement</h3>
<p>There are several reasons why a sender may want the acknowledgement of delivery
of a packet by the receiving chain.  For example, the sender may not know the
status of the destination chain, if it is expected to be faulty.  Or, the sender
may want to impose a timeout on the packet (with the <code>MaxHeight</code> packet field),
while any destination chain may suffer from a denial-of-service attack with a
sudden spike in the number of incoming packets.</p>
<p>In these cases, the sender can require delivery acknowledgement by setting the
initial packet status to <code>AckPending</code>.  Then, it is the receiving chain's
responsibility to confirm delivery by including an abbreviated <code>IBCPacket</code> in the
app Merkle hash.</p>
<p><a target="_blank" href="https://raw.githubusercontent.com/gnuclear/atom-whitepaper/master/msc/ibc_with_ack.png"><img src="https://raw.githubusercontent.com/gnuclear/atom-whitepaper/master/msc/ibc_with_ack.png" alt="Figure of Zone1, Zone2, and Hub IBC with acknowledgement" style="max-width:100%;"></a></p>
<p>First, an <code>IBCBlockCommit</code> and <code>IBCPacketTx</code> are posted on "Hub" that proves
the existence of an <code>IBCPacket</code> on "Zone1".  Say that <code>IBCPacketTx</code> has the
following value:</p>
<ul>
<li><code>FromChainID</code>: "Zone1"</li>
<li><code>FromBlockHeight</code>: 100 (say)</li>
<li><code>Packet</code>: an <code>IBCPacket</code>:
<ul>
<li><code>Header</code>: an <code>IBCPacketHeader</code>:
<ul>
<li><code>SrcChainID</code>: "Zone1"</li>
<li><code>DstChainID</code>: "Zone2"</li>
<li><code>Number</code>: 200 (say)</li>
<li><code>Status</code>: <code>AckPending</code></li>
<li><code>Type</code>: "coin"</li>
<li><code>MaxHeight</code>: 350 (say "Hub" is currently at height 300)</li>
</ul>
</li>
<li><code>Payload</code>: &lt;The bytes of a "coin" payload&gt;</li>
</ul>
</li>
</ul>
<p>Next, an <code>IBCBlockCommit</code> and <code>IBCPacketTx</code> are posted on "Zone2" that proves
the existence of an <code>IBCPacket</code> on "Hub".  Say that <code>IBCPacketTx</code> has the
following value:</p>
<ul>
<li><code>FromChainID</code>: "Hub"</li>
<li><code>FromBlockHeight</code>: 300</li>
<li><code>Packet</code>: an <code>IBCPacket</code>:
<ul>
<li><code>Header</code>: an <code>IBCPacketHeader</code>:
<ul>
<li><code>SrcChainID</code>: "Zone1"</li>
<li><code>DstChainID</code>: "Zone2"</li>
<li><code>Number</code>: 200</li>
<li><code>Status</code>: <code>AckPending</code></li>
<li><code>Type</code>: "coin"</li>
<li><code>MaxHeight</code>: 350</li>
</ul>
</li>
<li><code>Payload</code>: &lt;The same bytes of a "coin" payload&gt;</li>
</ul>
</li>
</ul>
<p>Next, "Zone2" must include in its app-hash an abbreviated packet that shows the
new status of <code>AckSent</code>.  An <code>IBCBlockCommit</code> and <code>IBCPacketTx</code> are posted back
on "Hub" that proves the existence of an abbreviated <code>IBCPacket</code> on
"Zone2".  Say that <code>IBCPacketTx</code> has the following value:</p>
<ul>
<li><code>FromChainID</code>: "Zone2"</li>
<li><code>FromBlockHeight</code>: 400 (say)</li>
<li><code>Packet</code>: an <code>IBCPacket</code>:
<ul>
<li><code>Header</code>: an <code>IBCPacketHeader</code>:
<ul>
<li><code>SrcChainID</code>: "Zone1"</li>
<li><code>DstChainID</code>: "Zone2"</li>
<li><code>Number</code>: 200</li>
<li><code>Status</code>: <code>AckSent</code></li>
<li><code>Type</code>: "coin"</li>
<li><code>MaxHeight</code>: 350</li>
</ul>
</li>
<li><code>PayloadHash</code>: &lt;The hash bytes of the same "coin" payload&gt;</li>
</ul>
</li>
</ul>
<p>Finally, "Hub" must update the status of the packet from <code>AckPending</code> to
<code>AckReceived</code>.  Evidence of this new finalized status should go back to
"Zone2".  Say that <code>IBCPacketTx</code> has the following value:</p>
<ul>
<li><code>FromChainID</code>: "Hub"</li>
<li><code>FromBlockHeight</code>: 301</li>
<li><code>Packet</code>: an <code>IBCPacket</code>:
<ul>
<li><code>Header</code>: an <code>IBCPacketHeader</code>:
<ul>
<li><code>SrcChainID</code>: "Zone1"</li>
<li><code>DstChainID</code>: "Zone2"</li>
<li><code>Number</code>: 200</li>
<li><code>Status</code>: <code>AckReceived</code></li>
<li><code>Type</code>: "coin"</li>
<li><code>MaxHeight</code>: 350</li>
</ul>
</li>
<li><code>PayloadHash</code>: &lt;The hash bytes of the same "coin" payload&gt;</li>
</ul>
</li>
</ul>
<p>Meanwhile, "Zone1" may optimistically assume successful delivery of a "coin"
packet unless evidence to the contrary is proven on "Hub".  In the example
above, if "Hub" had not received an <code>AckSent</code> status from "Zone2" by block
350, it would have set the status automatically to <code>Timeout</code>.  This evidence of
a timeout can get posted back on "Zone1", and any tokens can be returned.</p>
<p><a target="_blank" href="https://raw.githubusercontent.com/gnuclear/atom-whitepaper/master/msc/ibc_with_ack_timeout.png"><img src="https://raw.githubusercontent.com/gnuclear/atom-whitepaper/master/msc/ibc_with_ack_timeout.png" alt="Figure of Zone1, Zone2, and Hub IBC with acknowledgement and timeout" style="max-width:100%;"></a></p>
<h3><a id="user-content-merkle-tree--proof-specification" class="anchor" aria-hidden="true" href="#merkle-tree--proof-specification"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Merkle Tree &amp; Proof Specification</h3>
<p>There are two types of Merkle trees supported in the Tendermint/Cosmos
ecosystem: The Simple Tree, and the IAVL+ Tree.</p>
<h4><a id="user-content-simple-tree" class="anchor" aria-hidden="true" href="#simple-tree"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Simple Tree</h4>
<p>The Simple Tree is a Merkle tree for a static list of elements.  If the number
of items is not a power of two, some leaves will be at different levels.  Simple
Tree tries to keep both sides of the tree the same height, but the left may be
one greater.  This Merkle tree is used to Merkle-ize the transactions of a
block, and the top level elements of the application state root.</p>
<pre><code>                *
               / \
             /     \
           /         \
         /             \
        *               *
       / \             / \
      /   \           /   \
     /     \         /     \
    *       *       *       h6
   / \     / \     / \
  h0  h1  h2  h3  h4  h5

  A SimpleTree with 7 elements
</code></pre>
<h4><a id="user-content-iavl-tree" class="anchor" aria-hidden="true" href="#iavl-tree"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>IAVL+ Tree</h4>
<p>The purpose of the IAVL+ data structure is to provide persistent storage for
key-value pairs in the application state such that a deterministic Merkle root
hash can be computed efficiently.  The tree is balanced using a variant of the
<a href="http://en.wikipedia.org/wiki/AVL_tree" rel="nofollow">AVL algorithm</a>, and all operations are
O(log(n)).</p>
<p>In an AVL tree, the heights of the two child subtrees of any node differ by at
most one.  Whenever this condition is violated upon an update, the tree is
rebalanced by creating O(log(n)) new nodes that point to unmodified nodes of the
old tree.  In the original AVL algorithm, inner nodes can also hold key-value
pairs.  The AVL+ algorithm (note the plus) modifies the AVL algorithm to keep
all values on leaf nodes, while only using branch-nodes to store keys.  This
simplifies the algorithm while keeping the merkle hash trail short.</p>
<p>The AVL+ Tree is analogous to Ethereum's <a href="http://en.wikipedia.org/wiki/Radix_tree" rel="nofollow">Patricia
tries</a>.  There are tradeoffs.  Keys do
not need to be hashed prior to insertion in IAVL+ trees, so this provides faster
ordered iteration in the key space which may benefit some applications.  The
logic is simpler to implement, requiring only two types of nodes -- inner nodes
and leaf nodes.  The Merkle proof is on average shorter, being a balanced binary
tree.  On the other hand, the Merkle root of an IAVL+ tree depends on the order
of updates.</p>
<p>We will support additional efficient Merkle trees, such as Ethereum's Patricia
Trie when the binary variant becomes available.</p>
<h3><a id="user-content-transaction-types" class="anchor" aria-hidden="true" href="#transaction-types"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Transaction Types</h3>
<p>In the canonical implementation, transactions are streamed to the Cosmos hub
application via the ABCI interface.</p>
<p>The Cosmos Hub will accept a number of primary transaction types, including
<code>SendTx</code>, <code>BondTx</code>, <code>UnbondTx</code>, <code>ReportHackTx</code>, <code>SlashTx</code>, <code>BurnAtomTx</code>,
<code>ProposalCreateTx</code>, and <code>ProposalVoteTx</code>, which are fairly self-explanatory and
will be documented in a future revision of this paper.  Here we document the two
primary transaction types for IBC: <code>IBCBlockCommitTx</code> and <code>IBCPacketTx</code>.</p>
<h4><a id="user-content-ibcblockcommittx" class="anchor" aria-hidden="true" href="#ibcblockcommittx"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>IBCBlockCommitTx</h4>
<p>An <code>IBCBlockCommitTx</code> transaction is composed of:</p>
<ul>
<li><code>ChainID (string)</code>: The ID of the blockchain</li>
<li><code>BlockHash ([]byte)</code>: The block-hash bytes, the Merkle root which includes the
app-hash</li>
<li><code>BlockPartsHeader (PartSetHeader)</code>: The block part-set header bytes, only
needed to verify vote signatures</li>
<li><code>BlockHeight (int)</code>: The height of the commit</li>
<li><code>BlockRound (int)</code>: The round of the commit</li>
<li><code>Commit ([]Vote)</code>: The &gt;⅔ Tendermint <code>Precommit</code> votes that comprise a block
commit</li>
<li><code>ValidatorsHash ([]byte)</code>: A Merkle-tree root hash of the new validator set</li>
<li><code>ValidatorsHashProof (SimpleProof)</code>: A SimpleTree Merkle-proof for proving the
<code>ValidatorsHash</code> against the <code>BlockHash</code></li>
<li><code>AppHash ([]byte)</code>: A IAVLTree Merkle-tree root hash of the application state</li>
<li><code>AppHashProof (SimpleProof)</code>: A SimpleTree Merkle-proof for proving the
<code>AppHash</code> against the <code>BlockHash</code></li>
</ul>
<h4><a id="user-content-ibcpackettx" class="anchor" aria-hidden="true" href="#ibcpackettx"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>IBCPacketTx</h4>
<p>An <code>IBCPacket</code> is composed of:</p>
<ul>
<li><code>Header (IBCPacketHeader)</code>: The packet header</li>
<li><code>Payload ([]byte)</code>: The bytes of the packet payload. <em>Optional</em></li>
<li><code>PayloadHash ([]byte)</code>: The hash for the bytes of the packet. <em>Optional</em></li>
</ul>
<p>Either one of <code>Payload</code> or <code>PayloadHash</code> must be present.  The hash of an
<code>IBCPacket</code> is a simple Merkle root of the two items, <code>Header</code> and <code>Payload</code>.
An <code>IBCPacket</code> without the full payload is called an <em>abbreviated packet</em>.</p>
<p>An <code>IBCPacketHeader</code> is composed of:</p>
<ul>
<li><code>SrcChainID (string)</code>: The source blockchain ID</li>
<li><code>DstChainID (string)</code>: The destination blockchain ID</li>
<li><code>Number (int)</code>: A unique number for all packets</li>
<li><code>Status (enum)</code>: Can be one of <code>AckPending</code>, <code>AckSent</code>, <code>AckReceived</code>,
<code>NoAck</code>, or <code>Timeout</code></li>
<li><code>Type (string)</code>: The types are application-dependent.  Cosmos reserves the
"coin" packet type</li>
<li><code>MaxHeight (int)</code>: If status is not <code>NoAckWanted</code> or <code>AckReceived</code> by this
height, status becomes <code>Timeout</code>. <em>Optional</em></li>
</ul>
<p>An <code>IBCPacketTx</code> transaction is composed of:</p>
<ul>
<li><code>FromChainID (string)</code>: The ID of the blockchain which is providing this
packet; not necessarily the source</li>
<li><code>FromBlockHeight (int)</code>: The blockchain height in which the following packet
is included (Merkle-ized) in the block-hash of the source chain</li>
<li><code>Packet (IBCPacket)</code>: A packet of data, whose status may be one of
<code>AckPending</code>, <code>AckSent</code>, <code>AckReceived</code>, <code>NoAck</code>, or <code>Timeout</code></li>
<li><code>PacketProof (IAVLProof)</code>: A IAVLTree Merkle-proof for proving the packet's
hash against the <code>AppHash</code> of the source chain at given height</li>
</ul>
<p>The sequence for sending a packet from "Zone1" to "Zone2" through the
"Hub" is depicted in {Figure X}.  First, an <code>IBCPacketTx</code> proves to
"Hub" that the packet is included in the app-state of "Zone1".  Then,
another <code>IBCPacketTx</code> proves to "Zone2" that the packet is included in the
app-state of "Hub".  During this procedure, the <code>IBCPacket</code> fields are
identical: the <code>SrcChainID</code> is always "Zone1", and the <code>DstChainID</code> is always
"Zone2".</p>
<p>The <code>PacketProof</code> must have the correct Merkle-proof path, as follows:</p>
<pre><code>IBC/&lt;SrcChainID&gt;/&lt;DstChainID&gt;/&lt;Number&gt;

</code></pre>
<p>When "Zone1" wants to send a packet to "Zone2" through "Hub", the
<code>IBCPacket</code> data are identical whether the packet is Merkle-ized on "Zone1",
the "Hub", or "Zone2".  The only mutable field is <code>Status</code> for tracking
delivery.</p>
<h2><a id="user-content-acknowledgements" class="anchor" aria-hidden="true" href="#acknowledgements"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Acknowledgements</h2>
<p>We thank our friends and peers for assistance in conceptualizing, reviewing, and
providing support for our work with Tendermint and Cosmos.</p>
<ul>
<li><a href="https://github.com/zmanian">Zaki Manian</a> of
<a href="https://www.skuchain.com/" rel="nofollow">SkuChain</a> provided much help in formatting and
wording, especially under the ABCI section</li>
<li><a href="https://github.com/jtremback">Jehan Tremback</a> of Althea and Dustin Byington
for helping with initial iterations</li>
<li><a href="http://soc1024.com/" rel="nofollow">Andrew Miller</a> of <a href="https://eprint.iacr.org/2016/199" rel="nofollow">Honey
Badger</a> for feedback on consensus</li>
<li><a href="https://fixingtao.com/" rel="nofollow">Greg Slepak</a> for feedback on consensus and wording</li>
<li>Also thanks to <a href="https://github.com/gleim">Bill Gleim</a> and <a href="http://www.seunghwanhan.com" rel="nofollow">Seunghwan
Han</a> for various contributions.</li>
<li><strong>Your name and organization here for your contribution</strong></li>
</ul>
<h2><a id="user-content-citations" class="anchor" aria-hidden="true" href="#citations"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Citations</h2>
<ul>
<li><a href="https://bitcoin.org/bitcoin.pdf" rel="nofollow">1</a> Bitcoin: <a href="https://bitcoin.org/bitcoin.pdf" rel="nofollow">https://bitcoin.org/bitcoin.pdf</a></li>
<li><a href="http://zerocash-project.org/paper" rel="nofollow">2</a> ZeroCash: <a href="http://zerocash-project.org/paper" rel="nofollow">http://zerocash-project.org/paper</a></li>
<li><a href="https://github.com/ethereum/wiki/wiki/White-Paper">3</a> Ethereum: <a href="https://github.com/ethereum/wiki/wiki/White-Paper">https://github.com/ethereum/wiki/wiki/White-Paper</a></li>
<li><a href="https://download.slock.it/public/DAO/WhitePaper.pdf" rel="nofollow">4</a> TheDAO: <a href="https://download.slock.it/public/DAO/WhitePaper.pdf" rel="nofollow">https://download.slock.it/public/DAO/WhitePaper.pdf</a></li>
<li><a href="https://github.com/bitcoin/bips/blob/master/bip-0141.mediawiki">5</a> Segregated Witness: <a href="https://github.com/bitcoin/bips/blob/master/bip-0141.mediawiki">https://github.com/bitcoin/bips/blob/master/bip-0141.mediawiki</a></li>
<li><a href="https://arxiv.org/pdf/1510.02037v2.pdf" rel="nofollow">6</a> BitcoinNG: <a href="https://arxiv.org/pdf/1510.02037v2.pdf" rel="nofollow">https://arxiv.org/pdf/1510.02037v2.pdf</a></li>
<li><a href="https://lightning.network/lightning-network-paper-DRAFT-0.5.pdf" rel="nofollow">7</a> Lightning Network: <a href="https://lightning.network/lightning-network-paper-DRAFT-0.5.pdf" rel="nofollow">https://lightning.network/lightning-network-paper-DRAFT-0.5.pdf</a></li>
<li><a href="https://github.com/tendermint/tendermint/wiki">8</a> Tendermint: <a href="https://github.com/tendermint/tendermint/wiki">https://github.com/tendermint/tendermint/wiki</a></li>
<li><a href="https://groups.csail.mit.edu/tds/papers/Lynch/jacm85.pdf" rel="nofollow">9</a> FLP Impossibility: <a href="https://groups.csail.mit.edu/tds/papers/Lynch/jacm85.pdf" rel="nofollow">https://groups.csail.mit.edu/tds/papers/Lynch/jacm85.pdf</a></li>
<li><a href="https://blog.ethereum.org/2014/01/15/slasher-a-punitive-proof-of-stake-algorithm/" rel="nofollow">10</a> Slasher: <a href="https://blog.ethereum.org/2014/01/15/slasher-a-punitive-proof-of-stake-algorithm/" rel="nofollow">https://blog.ethereum.org/2014/01/15/slasher-a-punitive-proof-of-stake-algorithm/</a></li>
<li><a href="http://pmg.csail.mit.edu/papers/osdi99.pdf" rel="nofollow">11</a> PBFT: <a href="http://pmg.csail.mit.edu/papers/osdi99.pdf" rel="nofollow">http://pmg.csail.mit.edu/papers/osdi99.pdf</a></li>
<li><a href="https://bitshares.org/technology/delegated-proof-of-stake-consensus/" rel="nofollow">12</a> BitShares: <a href="https://bitshares.org/technology/delegated-proof-of-stake-consensus/" rel="nofollow">https://bitshares.org/technology/delegated-proof-of-stake-consensus/</a></li>
<li><a href="https://www.stellar.org/papers/stellar-consensus-protocol.pdf" rel="nofollow">13</a> Stellar: <a href="https://www.stellar.org/papers/stellar-consensus-protocol.pdf" rel="nofollow">https://www.stellar.org/papers/stellar-consensus-protocol.pdf</a></li>
<li><a href="https://interledger.org/rfcs/0001-interledger-architecture/" rel="nofollow">14</a> Interledger: <a href="https://interledger.org/rfcs/0001-interledger-architecture/" rel="nofollow">https://interledger.org/rfcs/0001-interledger-architecture/</a></li>
<li><a href="https://blockstream.com/sidechains.pdf" rel="nofollow">15</a> Sidechains: <a href="https://blockstream.com/sidechains.pdf" rel="nofollow">https://blockstream.com/sidechains.pdf</a></li>
<li><a href="https://blog.ethereum.org/2015/08/01/introducing-casper-friendly-ghost/" rel="nofollow">16</a> Casper: <a href="https://blog.ethereum.org/2015/08/01/introducing-casper-friendly-ghost/" rel="nofollow">https://blog.ethereum.org/2015/08/01/introducing-casper-friendly-ghost/</a></li>
<li><a href="https://github.com/tendermint/abci">17</a> ABCI: <a href="https://github.com/tendermint/abci">https://github.com/tendermint/abci</a></li>
<li><a href="https://github.com/ethereum/EIPs/issues/53">18</a> Ethereum Sharding: <a href="https://github.com/ethereum/EIPs/issues/53">https://github.com/ethereum/EIPs/issues/53</a></li>
<li><a href="http://www.ds.ewi.tudelft.nl/fileadmin/pds/papers/PerformanceAnalysisOfLibswift.pdf" rel="nofollow">19</a> LibSwift: <a href="http://www.ds.ewi.tudelft.nl/fileadmin/pds/papers/PerformanceAnalysisOfLibswift.pdf" rel="nofollow">http://www.ds.ewi.tudelft.nl/fileadmin/pds/papers/PerformanceAnalysisOfLibswift.pdf</a></li>
<li><a href="http://groups.csail.mit.edu/tds/papers/Lynch/jacm88.pdf" rel="nofollow">20</a> DLS: <a href="http://groups.csail.mit.edu/tds/papers/Lynch/jacm88.pdf" rel="nofollow">http://groups.csail.mit.edu/tds/papers/Lynch/jacm88.pdf</a></li>
<li><a href="https://en.bitcoin.it/wiki/Thin_Client_Security" rel="nofollow">21</a> Thin Client Security: <a href="https://en.bitcoin.it/wiki/Thin_Client_Security" rel="nofollow">https://en.bitcoin.it/wiki/Thin_Client_Security</a></li>
<li><a href="http://vitalik.ca/files/mauve_paper.html" rel="nofollow">22</a> Ethereum 2.0 Mauve Paper: <a href="http://vitalik.ca/files/mauve_paper.html" rel="nofollow">http://vitalik.ca/files/mauve_paper.html</a></li>
</ul>
<h4><a id="user-content-unsorted-links" class="anchor" aria-hidden="true" href="#unsorted-links"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Unsorted links</h4>
<ul>
<li><a href="https://www.docdroid.net/ec7xGzs/314477721-ethereum-platform-review-opportunities-and-challenges-for-private-and-consortium-blockchains.pdf.html" rel="nofollow">https://www.docdroid.net/ec7xGzs/314477721-ethereum-platform-review-opportunities-and-challenges-for-private-and-consortium-blockchains.pdf.html</a></li>
</ul>
</article>
  </div>

  </div>

  <button type="button" data-facebox="#jump-to-line" data-facebox-class="linejump" data-hotkey="l" class="d-none">Jump to Line</button>
  <div id="jump-to-line" style="display:none">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-jump-to-line-form" action="" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
      <input class="form-control linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
      <button type="submit" class="btn">Go</button>
</form>  </div>


  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>

    </div>
  </div>

  </div>

      
<div class="footer container-lg px-3" role="contentinfo">
  <div class="position-relative d-flex flex-justify-between pt-6 pb-2 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap ">
      <li class="mr-3">&copy; 2018 <span title="0.30002s from unicorn-3179495427-njd43">GitHub</span>, Inc.</li>
        <li class="mr-3"><a data-ga-click="Footer, go to terms, text:terms" href="https://github.com/site/terms">Terms</a></li>
        <li class="mr-3"><a data-ga-click="Footer, go to privacy, text:privacy" href="https://github.com/site/privacy">Privacy</a></li>
        <li class="mr-3"><a href="https://help.github.com/articles/github-security/" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li class="mr-3"><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a data-ga-click="Footer, go to help, text:help" href="https://help.github.com">Help</a></li>
    </ul>

    <a aria-label="Homepage" title="GitHub" class="footer-octicon" href="https://github.com">
      <svg height="24" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="24" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
   <ul class="list-style-none d-flex flex-wrap ">
        <li class="mr-3"><a data-ga-click="Footer, go to contact, text:contact" href="https://github.com/contact">Contact GitHub</a></li>
      <li class="mr-3"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li class="mr-3"><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li class="mr-3"><a href="https://blog.github.com" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a data-ga-click="Footer, go to about, text:about" href="https://github.com/about">About</a></li>

    </ul>
  </div>
  <div class="d-flex flex-justify-center pb-6">
    <span class="f6 text-gray-light"></span>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 0 0 0 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 0 0 .01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
    </button>
    You can’t perform that action at this time.
  </div>


    <script crossorigin="anonymous" integrity="sha512-AJroIDzeBTsez82UXWwVAmoSz2nKhws/uQvJ8aKfadJZcvL83MIXMjRYm7MVZaKSNXvifa/OGpn54kiDBKpyLw==" type="application/javascript" src="https://assets-cdn.github.com/assets/compat-37e9ce8318a51dd51033283da82c8546.js"></script>
    <script crossorigin="anonymous" integrity="sha512-REnv/1fvcM8kLoF0Q6pSR8eEDJgXBPo98lvK1sHUNXbBZURWGJoltSW1aZJ1sM+J++nppXioahrZr6ve9JjcFw==" type="application/javascript" src="https://assets-cdn.github.com/assets/frameworks-73770455a755e3bbebd0ce44e5036526.js"></script>
    
    <script crossorigin="anonymous" async="async" integrity="sha512-aniHEQIMNONswYQkRQogznZf4+1c+y2S34sL4tgoy7f+vUyUOZkJnHAGezxJmCKBIS/0bINRvqRJV/dg+02X4A==" type="application/javascript" src="https://assets-cdn.github.com/assets/github-74bb4e5ce59260d26c9d6154b2f40550.js"></script>
    
    
    
  <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner d-none">
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 0 0 0 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 0 0 .01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
    </button>
  </div>
</div>

  <div class="Popover js-hovercard-content position-absolute" style="display: none; outline: none;" tabindex="0">
  <div class="Popover-message Popover-message--bottom-left Popover-message--large Box box-shadow-large" style="width:360px;">
  </div>
</div>

<div id="hovercard-aria-description" class="sr-only">
  Press h to open a hovercard with more details.
</div>


  </body>
</html>

