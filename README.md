# University Digital Contact Website

## Project Description 
* Developed a searchable digital contact for the university. Streamlining information access for student, staff and visiting guest.

## Technical Stack
* User interfaces initalized by HTML, CSS and Boostraps.
* Backend handled by PHP.
* Using mySQL for storing data.
* Applied Laravel Framework.

## Demo Video


## Website Features
* Website's Authentication (Visiting Guest/ Staff)
    * Staff contains 2 roles (User/ Admin)
* Website's Authorization (User/ Admin)
    * User can update their information.
    * Admin has permission of Add/ Edit/ Delete information.
* Sign in
* Sign out
* Add/ Edit/ Delete/ Search Department contact information.
* Add/ Edit/ Delete/ Search Employee contact information.
* Advanced Search applied for searching employee (based on their Department, Address, Position).

## How to run code?
* Make sure you have PHP and Composer installed in your device.
* Clone the project to a folder.
``` properties
git clone https://github.com/dogiabao03/University_DigitialContact_Website
```
* Create a new database in your device
* Config the env. file to your database
```properties
DB_CONNECTION=
DB_HOST=
DB_PORT=
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=
```
* Run the migration file
```properties
php artisan migrate
```
* Run the server
``` properties
  php artisan serve
```

## License
MIT License

Copyright (c) 2024 BaoDo

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
 

  


