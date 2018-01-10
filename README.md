# couresera
<html>

<head>
  <title>Angular JS Controller</title>
  <script src = "https://ajax.googleapis.com/ajax/libs/angularjs/1.3.14/angular.min.js"></script>
  <script src="scriptS.js"></script>
</head>

<body>
  <h2>AngularJS Sample Application</h2>
  <div ng-app="ab" ng-controller="studentController">
    Food Name:<input type="text" ng-model="names" placeholder="Enter Two food Items to process"><br>
  <p ng-style='{color:cname}'>{{value}}</p>
  <button ng-click="process()">View Process</button>
 
  <!--    <ul> 
        <li ng-repeat="name in lnames">
        {{name}}
        </li>
    </ul>  


<form name="s" novalidate>  
    Last name:
      <input  name="lastname" type="text" ng-model="lastName" required>
        <span style="color:red" ng-show="s.lastname.$dirty &&s.lastname.$invalid">
           <span ng-show="s.lastname.$error.required">last Name is required</span>
        </span>
      <br>
    
    <div ng-include="'inc.html'"></div>
      
       
      <button ng-click="sub()" ng-disabled="s.lastname.$invalid||s.email.$dirty&&s.email.$invalid||s.email.$pristine||s.lastName.$pristine">Submit </button>
      <input type="reset" value="Reset">
      <p>{{final}}</p>
      

</form>
-->
  </div>
</body>

</html>
