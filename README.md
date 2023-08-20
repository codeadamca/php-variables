# A Basic Introduction to PHP and Variables

A basic example of using PHP variables.

This tutorial will review how to define and use PHP variables when creating HTML output. Here is a basic sample of using a variable and the `echo` command to create a personalized hello mesage.

```php
<?php 

$name = 'Jane Doe';
echo '<p>Hello '.$name.'!</p>';

?>
```

Variables are used to temporary store data and then reference that data later on in your code. For example, a visitor could fill out a contact form, the contact form data is then stored in a series of variables, and then later on could be used to display a personalized message and/or send a personalized email.

There are some rules when naming your variables:

- Variable names start with the `$` sign
- Variable names must start with a letter or an underscore
- Variable names can contain alpha-numeric characters and underscores
- Variable names are case-sensitive

## The End Goal

The goal of this series of lessons is to become comfortable with retrieveing data from a database and displaying the data in a web page. When working with database data the process roughly follows these steps:

1. Fetch data from the database.
2. Create a loop to iterate through the retrieved data.
3. Use if statements to check which data is ready for output.
4. Put the data into a series of variables and/or arays.
5. Use `echo` to output the variables and format them with HTML. 

In this lesson we're going to focus on the last step, outputting data using HTML, variables, and the `echo` statement.

## Steps

1. Open up a new file and name it variables.php.
2. Add the following code to the new PHP file:
    
    ```php
    <!doctype html>
    <html>
    <head>
        <title>Links and Variables</title>
    </head>
    <body>
        
        <h1>Links and Variables</h1>
        
        <p>Use PHP echo and variables to output the following link information:</p>
            
        <hr>
        
        <?php
        
        $linkName = 'Codecademy';
        $linkURL = 'https://www.codecademy.com/';
        $linkImage = 'codecademy.png';
        $linkDescription = 'Learn to code interactively, for free.';
        
        ?>
            
    </body>
    </html>
    ```

3. After the variables are defined use a series of `echo` statements to display the content. For example outputting the `$linkname` might look like this:
    
    ```php
    <?php
    
    echo '<h1>'.$linkName.'</h1>';
    
    ?>
    ```

Hint: Add each value from the array one at a time. Test your PHP after each new line of PHP. 

> [More information on PHP variables](https://www.php.net/manual/en/language.variables.variable.php)

> Full tutorial URL:  
> https://codeadam.ca/learning/php-variables.html

***

## Repo Resources

* [Visual Studio Code](https://code.visualstudio.com/) or [Brackets](http://brackets.io/) (or any code editor)
* [Filezilla](https://filezilla-project.org/) (or any FTP program)

<a href="https://codeadam.ca">
<img src="https://codeadam.ca/images/code-block.png" width="100">
</a>
