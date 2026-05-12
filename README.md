<!DOCTYPE html>
<html lang="en">
    
    <head> 
        <title>html fundamentals</title>
        <meta name="description" content="My first webpage"/>

        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">

        <script> 
            function sayHello() {
                alert("Hello from javascript!");
            }
        </script> 
    </head>
    <body>
        <div class="container">
            <h1 class="display-1">Hello Fundamentals!</h1>
            <h1 class="display-5">Second header</h1>
            
            <p id="p1" name="1p" class="lead">This is a simple paragraph.</p>
            <p id="p2" name="2p" class="lead">This is another simple paragraph.</p>
            <button class="btn btn-primary" onclick="sayHello()">Click me!</button>
        </div>
    </body>
</html>
    
