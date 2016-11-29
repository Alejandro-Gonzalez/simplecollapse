# SimpleCollapse.js
[demo](https://alejandro-gonzalez.github.io/simplecollapse/)
####Usage

Just add a link to the css file in your <head>:
```sh
<link rel="stylesheet" href="../css/compiled/simple_collapse.css" />
```
Then, before your closing <body> tag add:
```sh
<script src="https://code.jquery.com/jquery-3.1.1.min.js" ></script>
<script src="../js/simple_collapse.js"><script/>
```
####Initialize collapse/s
```sh
$(".collapse").collapse();
```

to initialize all collapses
or
```sh
$(".your_class").collapse();
```

to especific/s collapse

###Collapse Group Example
```sh
<div class="collapse_group">
      <div class="collapse">
          <div class="collapse__title">Collapse 1
              <div class="chevron"></div>
          </div>
          <div class="collapse__content open">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</div>
      </div>
      <div class="collapse">
          <div class="collapse__title">Collapse 2
              <div class="chevron"></div>
          </div>
          <div class="collapse__content">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</div>
      </div>
      <div class="collapse">
          <div class="collapse__title">Collapse 2
              <div class="chevron"></div>
          </div>
          <div class="collapse__content">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</div>
      </div>
    </div>
  
```
###Collapse Only Simple Example
```sh
<div class="collapse">
      <div class="collapse__title">Collapse 3
          <div class="chevron"></div>
      </div>
      <div class="collapse__content open">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </div>
  </div>
```
