<h1>To run the project create use below comand one by one</h1>
<ul>
  
  <li>git init </li>
   
   <li>git clone https://github.com/CodeUpSubodh/BlogProjectDjango.git</li>
    <li>virtualenv env</li>
     <li>Set-ExecutionPolicy Unrestricted -Scope Process</li>
      <li>./env/scripts/activate</li>
       <li>pip install -r requirements.txt</li>
        <li>python manage.py make migrations</li>
        <li>python mange.py migrate</li>
        <li>python manage.py runserver</li>
 
  
</ul>
<h1>To run admin portal run</h1>


<l1>Enter URL http://127.0.0.1:8000/admin after running the server</l1>
<li>Enter ID as admin and password as 123</li>
<li>If not working type "python manage.py createsuperuser" comand on terminal and set Id password for admin </li>
