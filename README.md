# Unit ４ Project: home brewry lecip 

 ## Criteria A: Planning

## Problem definition(Client identification)

私が今直面している問題が、私が作っているビジネスがホームブリューイングのキットを来るというものです。これをするに合ったって、現状日本ではホームブリューイングという文化が無いため。ビールのレシピを共有するソーシャルメディアが存在しないことに気が付きました。ここのブログなどでは、ビールのレシピやオリジナルな作り方を紹介しているものは存在しているものの。そのような情報を統合しているソーシャルメディアがあることでよりホームブリューイングの文化がより日本に根付かせることができます。そして、ビールにはとても個々のオリジナリティや地域性が出るものです。例えば、ホップ、麦芽をどこのものを使うかや、副原料をどのようなものを使うのか。そして、二次発酵時のブースト剤にどのような糖を使うのかなど多岐に渡ります。そのような情報やメソッドを、ホームブリューイングをしている人同士でシェアすることが難しいのが現状です。そして、安全でセキュアで整理されらプラットフォームが限られています。醸造所に行ったり、ビールづくり体験会などに行かない限りその情報を得ることができないのが現状です。その証拠として、実際にクライアントとの協議したメールをフォルダーに載せておきます。

## Proposed Solution
私達の提案する解決策は、HTML SCC、そしてこのPythonを使用してウェブベースのソーシャルメディアを作成することです。このサイトは、ホームブリューイングの文化を日本で広め、ユーザーがビールのレシピや独自の製法を共有できるプラットフォームを提供します。


## Raatinale for propsed solution
このプロジェクトは、ホームブリューイングの文化がにひおんでまだ一般的でない問題に対して解決します。ウェブベースのソーシャルメディアサイトにより、情報やメソッドを簡単に共通できるようになりｍこのホームブリューイングに興味を持つ人々がある丸コミュニティが形成されることが予想できます。
問題提議で述べたように、現在日本ではホームブリューイングにかんする情報得るのが難しいです。このウェブベースのソーシャルメディアにより、情報やメソッドを簡単に情報やアイデアを共有できる場を提供します。
データ管理の観点kら、このプロジェクトでは、ユーザーがアップロードしたレシピやその画像、データを保存・管理するためのベータベースを設計します。Pythonで実装されたバックエンドシステムが、データの追加、編集、削除などの操作を処理します。
HTMLとCSSはウェブサイトの基本的な構造とスタイルを構築するために選択され、Pythonはバックエンドの開発のために選びました。これらの技術はプロジェクトの文脈にてきしており、開発者の経験だけでなく、多く使われている技術です。
代替の方法として、PHPやJavaScriptなどの他のプログラミング言語を使用することもできますが、Pythonはその簡潔さと拡張性で知られており、データ処理やデータベース操作に適しています。また、PythonのフレームワークであるDjangoやFlaskは、ウェブ開発を容易にするたｍの追加機能を提供します。
私はプロジェクトの実施に先立って、提案された解決策と使用されるツールに関する調査を行いました。HTMLとCSSはウェブデザインの基本であり、Pythonはバックエンド開発において一般的な選択肢です。また、Pythonのフレームワーク（DjangoおよびFlask）は、ウェブアプリケーション開発を容易にする追加機能を提供しており、多くの成功したプロジェクトで使用されています。データベースは、SQLiteが適していると思います。SQLAlchemyのインターフェースは、パフォーマンスが向上し、セキュリティ攻撃から保護されているため、SQLAlchemyを選択することにしました
さらに、類似のソーシャルメディアプラットフォームやビール愛好家向けのウェブサイトを調査し、ユーザーエクスペリエンスの良い実践方法や機能を参考にしました。これにより、私たちの提案されたソリューションが実現可能で効果的であるという確信を持つことができました。

最後に、私たちはプロジェクトの成功に向けて、適切なデータ管理とプライバシー保護にも焦点を当てます。これには、データベース設計、セキュリティ対策、およびユーザーの権限管理が含まれます。このようにして、私たちのウェブベースのソーシャルメディアサイトは、日本のホームブリューイングコミュニティにとって信頼できる情報源となることが期待されます。


### Design Statement
私は、ホームブリューイングの情報を共有したいと思っているビール愛好家のクライアント向けに、ウェブベースのソーシャルメディアサイトを設計・制作します。このSNSは、ビールのレシピや独自の製法を共有・閲覧することを目的としており、CSS、HTML、およびPythonを使用して構築されます。制作期間は4週間を見込み、評価基準A、B、C、D、およびEに従って評価されます。"



## Success Criteria

Success Criteria:

1. ウェブサイトは、ユーザーがビールのレシピや製法を投稿できるようにする必要があります（問題対処: "ビールのレシピを共有するソーシャルメディアが存在しない"）。
2. ウェブサイトは、ホームブリューイングに関連する情報やリソースを統合し、ユーザーが簡単にアクセスできるようにする必要があります（問題対処: "醸造所に行ったり、ビールづくり体験会などに行かない限りその情報を得ることができない"）。
3. ウェブサイトは、ユーザーが他のホームブリュワーとコミュニケーションを取り、情報や製法を共有できるようにする必要があります（問題対処: "ホームブリューイングをしている人同士でシェアすることが難しい"）。
4. ウェブサイトは、個々のビールのオリジナリティや地域性を強調し、ユーザーがそれらの要素を探求できるようにする必要があります（問題対処: "ビールにはとても個々のオリジナリティや地域性が出るものです"）。
5. ウェブサイトは、セキュアなログインと登録機能を提供し、ユーザーのプライバシーを保護する必要があります（問題対処: "セキュアで整理されたプラットフォームが限られている"）。
6. ウェブサイトは、ユーザープロファイルページを提供し、プロファイルのカスタマイズができるようにする必要があります（問題対処: "ホームブリューイングの文化がより日本に根付かせることができます"）。

# Criteria B: Design

## System Diagram

![](49.jpg)
<i>Fig. １</i> This is the wireframe for the application. 

It serves as a visual representation of the system and its components, and their relationships to each other. As shown above, the application will run on Python and KivyMD. The application will have various inputs from the user, which will all be stored within a database using SQLite. All of this will be executed within the Pycharm application, which will then display the output on a screen




## Wireframe

![](IMG_1318.JPG)
<i>Fig. 2</i> This is the wireframe for the application. 

As shown in Figure 2, the wireframe details the appearance of the application. The wireframe also details the plan for how the different screens will be displayed by the different buttons. Arrows extending from the buttons to the screen serve to indicate which screen will open when the user presses and then releases the button. With two exceptions, the "Search Flight" screen and the "Table" screen will open whichever browser opens and jumps to the URL when the user clicks on the "Search" (search flight screen) or "Table View" URL. The purpose of this wireframe diagram is to visually represent the user interface design outlining the structure and layout of the application.

## ER Diagram
![](IMG_1320.JPG)
<i>Fig. 3</i> This is the wireframe for the application. 

## UML Diagram
![](UML.png)
<i>Fig. 5</i> This is the wireframe for the application. 
This is a UML diagram of the application, showing the classes and methods used in its development. The diagram contains two main parent classes: MDApp and MDScreen. All subclasses inherit methods and attributes from these parent classes, as indicated by the arrows in the diagram.

The database_worker class in the figure provides methods for establishing a connection to the SQLite3 database, retrieving information in the database, saving information to the database, and closing the connection to the database.

## Flow diagram
![](flow1.png)
<i>Fig. 5</i> This is the wireframe for the application. 


![](flow2.png)
<i>Fig. 6</i> This is the wireframe for the application. 


![](flow3.png)
<i>Fig. 7</i> This is the wireframe for the application. 
## Record of Tasks

| No. | Task                                          | Planned Outcome                                                                                                                                | Time Estimate | Target Completion date | Criterion |
|-----|-----------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|---------------|------------------------|-----------|
| 1   | First meeting with client                     | Identify problem, set up future meeting(s)                                                                                                     | 10 min        | Feb 11                | A         |
| 2   | Create proposed solution and success criteria | Create a detailed proposed solution and success criteria to client's problem, send to client for confirmation                                  | 20 min        | Feb 12                | A         |
| 3   | Research rationale                            | Research and create a logical rationale behind the tools used for the proposed solution                                                        | 40 min        | Feb 12                | A         |
| 4   | Create login page                             | Program the kivymd and python files for the GUI and functionality of the login page                                                            | 3 hr          | Feb 15               | C         |
| 5   | Create registration page                      | Program the kivymd and python files for the GUI and functionality of the registration page                                                     | 2 hr          | Feb 15               | C         |
| 6   | Create wireframe diagram                      | Design the wireframe diagram of the application                                                                                                | 30 min        |  Feb 27               | B         |
| 7   | Create system diagram                         | Design the system diagram of the application                                                                                                   | 30 min        | Feb 27               | B         |
| 8   | Create ER table and diagram                   | Design the ER table and diagram for the application                                                                                            | 30 min        | Feb 27               | B         |
| 9   | Create homescreen page                           | Program the kivymd and python files for the GUI and functionality of the main menu                                                             | 3 hr          | March 3                | C         |
| 10  | Create database                               | users (users, id, email,name) using SQLAlchemy ORM                                                                   | 2 hr          | April 3                | C         |
| 11  | Create password hashing function              | Create a function to encrypt user passwords for security                                                                                       | 30 min        |  March 3                | C         |
| 12  | Create first table screen                     | Program the kivymd and python files for the GUI and functionality of the first table screen, which displays the log of borrowers               | 3 hr          | MArch 5               | C         |
| 13  | Create first table screen input               | Program the kivymd and python files for the GUI and functionality to input data into the first table                                           | 3 hr          |  March 7               | C         |
| 14  | Create second table screen                    | Program the kivymd and python files for the GUI and functionality of the second table screen, which displays the songs appliance information | 2 hr          | March 10               | C         |
| 15  | Create second table screen input              | Program the kivymd and python files for the GUI and functionality to input data into the second table                                          | 2 hr          | March 10              | C         |
| 16  | Create flow diagrams                          | Design 3 flow diagrams to showcase modules of functionality from the python file                                                               | 30 min        | March 10               | B         |
| 17  | Clean up code                                 | Final bug fixes and commenting, good coding practices                                                                                          | 1 hr          |  March 10               | C         |
| 18  | Final testing                                 | Final functionality testing by following the test plan                                                                                         | 30 min        |  March 10               | D         |
| 19  | Create demonstration video                    | Create video showcasing complete functionality of the application                                                                              | 1 hr          |  March 10              | D         |
## Flow Diagrams


## Test Plan

Test Plan

| Type                | Description                | Process                                                      | Anticipated Outcome                                          |
| ------------------- | -------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Unit Testing        | User Registration          | 1. Open the website<br/>2. Click on the register button<br/>3. Enter a valid username and password, and click the register button | The modal should disappear and a flash message should appear stating that the user has been registered successfully. |
| Unit Testing        | User Login                 | 1. Open the website<br />2. Enter valid credentials and click the login button on the login card | The user should be redirected to the dashboard page of the website if the user exists and the password matches the hash in the database. |
| Unit Testing        | Logout                     | 1. Open the website<br />2. Login using valid credentials<br />3. Click the log out button on the top bar | The user should be redirected back to the login screen and the session token should be removed from the session storage if checked using "Inspect". |
| Integration Testing | Login and Registration     | 1. Open the website<br />2. Follow the instructions for registering a user above<br />3. Follow the instructions for logging in above using the same credentials that were registered with<br /> | If the user followed the instructions properly and registered for a user, then the user should be able to login with the same credentials that were just registered with. |
| Unit Testing        | Changing Password          | 1. Open the website<br />2. Login using valid credentials<br />3. Click on the my profile button on the header<br />4. Click the change password button<br />5. Input the current password of the current user and put a new password<br />6. Click Confirm | If the user followed the instructions properly and no errors occurred in the process, then the user should be able to logout and log back into the same user with the same username but with the new password. |
| Unit Testing        | Adding new post            | 1. Open the website<br />2. Login using valid credentials<br />3. Click New Post on the header<br />4. Fill in the required fields for a new post<br />5. Click the submit button | The user should be redirected to their own profile page, where they can see their own posts, including the one they just posted. |
| Unit Testing        | Like/Dislike a post        | 1. Open the website<br />2. Login using valid credentials<br />3. Click on the like button of a post<br />4. Click on the dislike button of another post | The user should be able to see the like count of the post increase by 1 for the first post and decrease by 1 for the second one. |
| Integration Testing | Adding Post / Viewing Post | 1. Open the website<br />2. Login using valid credentials<br />3. Create a new post following the instructions above<br />4. Click the home button | The user should be able to see the post they just created on the top of the dashboard. |
| Unit Testing        | Sorting System             | 1. Open the website<br />2. Login using valid credentials<br />3. Change the sorting method to sort by like count on the dashboard using the dropdown on the right | The user should be able to see posts sorted by the highest like count. |
| Code Review         | Reviewing Code             | Going through the code and making sure unused parts are removed, variables are named properly and comments are placed appropriately | Easy to understand and easy to debug code for future development. |


# Criteria C: Development

## Existing Tools

| Software/Development Tools | Coding Structure Tools  | Libraries  |
| -------------------------- | ----------------------- | ---------- |
| PyCharm                    | OOP Structures(Classes) | Kivymd.app |
| Python                     | SQL requests            | Passlib    |
| SQLite                     | Databases               | sqlalchemy |
| KivyMD                     | Encryption              |            |
| ChatGPT                    | For Loops               |            |
|                            | If-then-else statements |            |





## Development

### OOP

#### Object Oriented Programming

The Apprication was constructed using Object-Oriented Programming (OOP) principles to improve its modularity, reliability, and maintainability. OOP is a programming paradigm that emphasizes the creation of objects, which are instances of classes that encapsulate both data and behavior. By using classes, the code is organized into reusable and modular components that can be easily extended or modified.

In this app, each component of the application, such as the GUI, database, and user inputs, is encapsulated in its own class. This allows for easier debugging and troubleshooting since each class can be tested independently of the others. Moreover, changes and updates to the application can be made without affecting other parts of the code.

Additionally, OOP allows for the use of abstraction and polymorphism, which make the code more flexible and adaptable. Abstraction refers to the ability to hide implementation details and focus on the essential features of an object, while polymorphism allows objects of different classes to be used interchangeably.

Overall, the use of OOP in the Vocabulary App improves its overall design, making it more organized, modular, and flexible. It also makes it easier for future developers to maintain and extend the application with new features.


```.py
class database_worker:
    def __init__(self, name):
        self.connection = sqlite3.connect(name)
        self.cursor = self.connection.cursor()

    def search(self, query):
        result = self.cursor.execute(query).fetchall()
        return result

    def run_save(self, query):
        self.cursor.execute(query)
        self.connection.commit()

    def close(self):
        self.connection.close()
```
In this way, each action is contained under a function for each screen class, making it very easy to understand.


#### ORM

Object-Relational Mapping (ORM) is a programming technique that allows developers to manipulate relational databases using an object-oriented programming paradigm. A relational database is a database that stores structured data organized in tables and columns. In traditional programming, developers need to write SQL code to interact with the database using SQL statements to retrieve, update, and delete records in the database. With an ORM, however, developers can interact with the database using an object-oriented approach; the ORM framework provides a layer of abstraction between the application and the database. This eliminates the need for developers to write SQL code to deal with the database.

The ORM framework maps database tables to application classes and columns to class properties. This allows developers to manipulate the database by simply manipulating the classes, without the need to write SQL code to interact with the database. For example, consider the following Python code.

```,py
SELECT *
FROM users
WHERE name = "Gentaro"
```
This is a normal SQL statement that can be executed in python through running a query with the sqlite3 library. This is a language with a low level of abstraction.


### DEvelopment of User interface Using KivyMD

### Screen Manager
```py
ScreenManager:
    LoginScreen:
        name: "LoginScreen"
    SignupScreen:
        name: "SignupScreen"
    HomeScreen:
        name :"HomeScreen"
    SearchScreen:
        name :"SearchScreen"
    AddScreen:
        name :"AddScreen"
    TableScreen:
        name :"TableScreen"
```
My client has created a list of his favorite songs and his goal is to be able to listen to those songs through a URL from that list. Therefore, in developing the user interface, GIU is the best fit for this need because it is easy and intuitive to use.

Kivycode above created the "LoginScreen,SignupScreen,HomeScreen,SearchScreen,AddScreen,TableScreen" screens for these applications. In addition, unique names and IDs were defined in the Screen Manager.

Each screen uses and defines a separate kivy code block that provides the layout and widgets for that screen. As an example, the "SearchScreen" contains a text input field from which you can search for each item. Also, in the "TableScreen," songs added by the user are displayed for each item. Then, by tapping the URL displayed there, the user can jump to that URL and listen to the song.

Defining each screen as a separate widget is possible with ScreenManager. And because it is possible to switch screens on the liverpool and treat each screen as a separate one. As an example, when a user logs in, he/she can switch from "LoginScreen" to "HomeScreen" by pressing a button. This structure of the GUI results in a very organized and intuitive interface that is easy to use for both users and developers.

## General Application Screen for Kivy

### SignupScreen
```.py
<SignupScreen>:
     size: 500,500
        FitImage:
            source:"main_image.jpeg"
        MDCard:
            size_hint: .8, .9
            elevation: 2
            orientation: "vertical"
            pos_hint: {"center_x": .5, "center_y":.5}
            padding: dp(50)      
        
 ```
 
MDcard is a component of the KivyMD library and represents a rectangular card with rounded corners, within which other widgets can be placed. the MDcard is drawn as a percentage of the MDcard that is tightened on the screen, and also this MDcard is drawn perpendicular to the screen The MDcard is drawn perpendicular to the screen. It also depicts the spacing of this MDcard relative to the screen and what percentage of the center of the screen this MDcard will be located. This information is entered and drawn as a visual layout. This kivy code block was adopted as the basic configuration for each screen. All screens have the same setup and background screen.


### MDLabel
```.py
MDLabel:
            text: "WELCOME YOUR MUSIC"
            font_style: "H5"
            size_hint: 1, .1
            font_size:90
            halign: "center"
            pos_hint: {"center_x": .5, "center_y": .5}
```

The MDLabel is a customizable on-screen text label that is widely used in modern applications to convey important information to users. It is an essential UI element that serves as an indicator to guide the user and provide context to the content being displayed on the screen.

In this particular case, the MDLabel is being utilized as the title of the home page screen, making it the first thing the user sees when they enter the home screen. The label's role is to provide the user with a clear understanding of where they are within the application, which is crucial for a seamless user experience.

This MDLabel can be customized in terms of its text color, font, size, and style to align with the overall theme of the application. The label's flexibility makes it an essential component of any application, allowing developers to design visually appealing screens with a clear and concise message. Ultimately, the MDLabel serves as an essential tool for designers and developers alike to enhance the user's experience and create a successful application.

### MDFillRoundFlatIconButton
```.py
MDFillRoundFlatIconButton:
                icon: "music-circle-outline"
                text: "Add your songs"
                font_size: 30
                on_release: app.root.current = 'AddScreen'
                md_bg_color: "f6bd60"
                pos_hint: {"center_x": .5, "center_y": .5}
```


The KV code above shows the implementation of the MDFillRoundFlatIconButton, a multifunctional button often used in modern UI design to create visually appealing and user-friendly interfaces. The button is designed with a circular, flat icon and is often used for interactive elements that need to be quickly accessed, such as home screen buttons and navigation menus.

The MDFillRoundFlatIconButton provides a clean, professional aesthetic that is in line with client needs. The shape and style of this button provides a modern, sleek design that enhances the overall user experience. Additionally, the circular shape of the button adds a unique touch to the interface and helps distinguish it from other standard rectangular buttons.

This button is a popular choice among designers and developers because it can be easily customized to fit the design requirements of any application. MDFillRoundFlatIconButton can be adjusted to match the application's color scheme, text size, font style MDFillRoundFlatIconButton can be adjusted to match your application's color scheme, text size, and font style, resulting in a consistent and cohesive interface.



### MDRaisedButton
```.py
MDRaisedButton:
            id : addsongs
            text:"Add Songs"
            size_hint: 3,1
            md_bg_color: "#a8dadc"
            on_press:
                root.manager.current = "AddScreen"
                root.manager.transition.direction = "left"
```

MDRaisedButton is a rectangular button. It features a 3D-like visual effect and has a raised or slightly elevated appearance. It is often used for more important or attention-grabbing actions within an application. unlike the MDFillRoundFlatIconButton, the MDRaisedButton is not circular in shape and can be customized to include text or an icon.

Both buttons can be customized to meet the design requirements of the application, but which one to use depends on the specific use case and the desired look and feel of the interface. In general, MDFillRoundFlatIconButton is better suited for home screen buttons and navigation menus, while MDRaisedButton is better suited for actions that require a more prominent or attention-grabbing appearance.


### MDTextField
```.py
 MDTextField:
                id: search
                hint_text: "Search"
                size_hint: 1, .17
                required: True
```

MDTextField is a fundamental component of the modern user interface that allows users to enter information through the keyboard. This type of text field is an essential element of applications that require data entry by the user, such as account registration, data entry forms, and search boxes.

When programming MDTextFields, it is important to consider the possibility of user error during data entry. To address this issue, designers and developers can use helper text and error messages to guide users through the data entry process. As shown in the figure above, helper text is displayed to prompt the user to enter information if he or she forgets to do so. Additionally, if an error occurs during data entry, the error message is displayed in red to alert the user.

An important aspect of designing MDTextFields is the size hint property, which specifies the size of the text field. The size hint can be set to a specific value, such as "1,.17" to ensure that the text field is large enough for the user to enter information without problems. If the size hint is set to a value that is too small, the user may have difficulty entering text properly, leading to errors and frustration.


## Development of Application Using Python

### Database configuration

```.py
class database_worker:
    def __init__(self, name):
        self.connection = sqlite3.connect(name)
        self.cursor = self.connection.cursor()

    def search(self, query):
        result = self.cursor.execute(query).fetchall()
        return result

    def run_save(self, query):
        self.cursor.execute(query)
        self.connection.commit()

    def close(self):
        self.connection.close()
```
This code defines a Python class called database_worker. This class has a __init__ method that takes one argument, name, which specifies the name of the SQLite database. This method initializes a connection to the specified database in the connection attribute and a cursor object that can be used to execute SQL statements on the database in the cursor attribute.

The class also has a search method that takes one argument, a query, which is an SQL query to be executed on the database. This method executes the query using the cursor object and fetches all results using the fetchall method. The method then returns the results as a list of tuples.

The class also has a run_save method that takes one argument, a query, which is an SQL query to be executed on the database. This method executes the query using a cursor object and commits the changes to the database.

Finally, the class has a close method that closes the connection to the database.


### Registration System


#### Password Match Confirmation
```.py
    def try_register(self):
        uname = self.ids.uname.text
        email = self.ids.emails.text
        passwd = self.ids.passwd.text
        passwd2 = self.ids.passwd2.text
```
This code defines a method called try_register that is used to register a new user in a system. It retrieves the user's input for their desired username, email, password, and password confirmation from the corresponding text input widgets in the GUI using self.ids.

The input is stored in the variables uname, email, passwd, and passwd2, respectively. uname is short for username, email refers to the email address the user enters, passwd is short for password, and passwd2 is used to confirm that the user has entered the correct password.

After retrieving the input values, the method proceeds to validate the input by checking if the password and password confirmation fields match. The registration process cannot proceed if the passwords do not match.

This method is commonly used in user registration systems to capture user input and validate that the information entered is accurate before proceeding with account creation.

#### Insert user information into the database
```.py
        if passwd != passwd2:
            self.ids.passwd.error = True
            self.ids.passwd2.error = True
        else:
            hash = encrypt_password(passwd)
            db = database_worker("project3_db.db")
            query = f"INSERT into users (email, password, username) values('{email}','{hash}','{uname}')"
            db.run_save(query)
            db.close()
            print("Registration complete")
            self.parent.current = "LoginScreen"
```
When a user is trying to create a new account, this code validates the information entered and processes it to insert the user information into the database.

First, it checks if the passwords entered match. If it does not match, an error is displayed in the password entry field.

If it matches, the password is hashed and the new user information is inserted into the database. To do so, it generates an SQL query containing the user name, email address, and hashed password, and queries the database using the database_worker class. Then close the database connection.

Finally, it displays a message indicating that the new user was successfully created and returns to the login screen.

### Login System

#### passward reset
```.py
    def cancel(self):
        self.ids.passwd.text = ""
        self.ids.passwd2.text = ""
        self.parent.current = "LoginScreen"
```
This code provides the ability to reset the password on the user registration screen and return to the login screen. cancel method empties the text in the password entry field and changes the application's current screen to LoginScreen. This allows the user to re-enter the password and cancel the registration.


### Registration System

#### Pulling user information from the database
```.py
    def try_login(self):
        print("User trying to login")
        uname = self.ids.uname.text
        passwd = self.ids.passwd.text
        query = f"SELECT * from users WHERE username = '{uname}'"
        db = database_worker("project3_db.db")
        result = db.search(query=query)
        db.close()
        print(result)
 ```       

The code attempts to log in a user by checking if the username entered exists in the database and if the password entered matches the password stored in the database under that username.

#### User Credential Verification
```.py
        if len(result)==1:
            pass
            hashed = result[0][2]
            if check_password(user_password=passwd, Hashed_password=hashed):
                print("Login successful")
                self.parent.current = "HomeScreen"
```
The code checks whether the length of the result returned from the database is equal to 1, indicating that a user with the entered username exists in the database. If so, the hashed password associated with that user name is retrieved from the database and the "check_password" function is used to check whether the entered password matches the stored hashed password. If the password matches, the user is logged in and the screen switches to the home screen.


#### passward reset
```.py
    def cancel(self):
        self.ids.passwd.text = ""
        self.ids.passwd2.text = ""
        self.parent.current = "LoginScreen"
```
This code provides the ability to reset the password on the user registration screen and return to the login screen. cancel method empties the text in the password entry field and changes the application's current screen to LoginScreen. This allows the user to re-enter the password and cancel the registration.


### Adding System


```.py
    def Addsongs(self):
        song_title = self.ids.song_title.text
        release_date = self.ids.release_date.text
        artist_name = self.ids.artist_name.text
        genre = self.ids.genre.text
        song_link = self.ids.song_link.text
```
#### Variable Definitions
This code defines a function called "Addsongs" that extracts input data for a new song from various text input fields using their corresponding ids. The input data includes the song title, release date, artist name, genre, and song link. These variables are used to construct an SQL query for inserting the new song into a database table.


##### Insert Query
```.py 
    def Addsongs(self):
        song_title = self.ids.song_title.text
        release_date = self.ids.release_date.text
        artist_name = self.ids.artist_name.text
        genre = self.ids.genre.text
        song_link = self.ids.song_link.text

        db = database_worker("project3_db.db")
        query = f"INSERT into songs (song_title, release_date,artist_name,genre,song_link) values('{song_title}','{release_date}','{artist_name}','{genre}','{song_link}')"
        db.run_save(query)
        db.close()
        print("Song added")
```

This code inserts flight information provided by variables flight_number, destination, date, flight_schedule, terminal, gate_number, and status into a database table called "allflights" using an SQL query constructed using the query variable, executed using the run_save method of the database connection created with the database_worker function, and saved to the database file "unit3project.db". The close method is used to close the database connection after the query has been executed, and a message is printed to indicate that the flight has been added to the database.

### Table of songs 

#### Data Table

```.py
self.data_table = MDDataTable(
            size_hint=(0.9, 0.7),
            pos_hint={"center_x": 0.5, "center_y": 0.5},
            use_pagination=True,
            check=True,
            column_data=[
                ("ID", 50),
                ("Song title", 40),
                ("Release date", 40),
                ("Artist name", 40),
                ("Genre", 40),
                ("Song link", 160)
            ],
            row_data=[]
        )
        self.add_widget(self.data_table)
        self.data_table.bind(on_row_press=self.on_row_press)
        self.update()
```
This code is designed to display a table on the screen that contains data, with the aim of allowing the user to view and interact with the data in a clear and organized way. In order to provide the client with the ability to listen to a song from their own list of favorite songs, this code uses the "self.data_table.bind(on_row_press=self.on_row_press)" method to enable the user to click on a specific song URL displayed on the table, which will trigger the "on_row_press" function to execute and redirect the user to the corresponding URL. This functionality is essential for providing a smooth and seamless user experience and ensures that the client can easily navigate to the song they want to listen to from their list of favorite songs.



#### Press an item in a table
```.py
@staticmethod
    def on_row_press(table, row):
        print(f"Row was pressed. Data is: {row.text}")
        if row.text.find("http") == -1:
            temp = f"https://{row.text}"
        else:
            temp = row.text
        result = urlparse(temp)
        print(result)
        print(all([result.scheme, result.netloc, result.path]))
        if all([result.scheme, result.netloc, result.path]) is True:
            webbrowser.open(temp)
            print("reached")
        else:
            pass

    @staticmethod
    def on_check_press(table, current_row):
        print(f"Row {current_row} was checked")
```

This code defines methods for manipulating tables using Kivy, a Python GUI framework. Specifically, it defines the on_row_press method, which is called when a table row is selected, and the on_check_press method, which is called when a table row is checked.

The on_row_press method performs a specific operation on the table and row passed as arguments. This method retrieves the data for the selected row, checks to see if it is a URL, and if so, parses the URL to open it in a web browser and calls webbrowser.open. This method is declared as a static method, so it can be called directly without creating an instance of the class.

The on_check_press method performs specific processing on the table and current_row passed as arguments. This method retrieves information about the checked row and outputs a message to confirm that it has been selected. This method is also declared as a static method, so it can be called directly without creating an instance of the class.

### Deleting Table

```.py
    def delete(self):
        rows_checked = self.data_table.get_row_checks()
        print("Trying to delete")
        print(rows_checked)
        db = database_worker("project3_db.db")
        for r in rows_checked:
            id = r[0]
            query = f"delete from songs where id = {id}"
            db.run_save(query)
        db.close()
        self.update()
```
This code implements the function of deleting data from the database: the delete() method retrieves the data for the rows checked by the user and deletes those rows from the database. First, it uses the get_row_checks() method of the data_table object to obtain a list of checked rows. Then, using the IDs of the retrieved rows, we create an SQL query to delete the corresponding rows from the songs table and send it to the database using the database_worker class. Finally, the update() method is used to update the data and display the latest data.

Specifically, it stores the list of rows checked by the user in rows_checked. It then connects to the database and executes a delete query on each row in the rows_checked list using a for loop. Using the ID of the deleted row, the SQL query deletes the corresponding row in the songs table. To reflect the changes to the database, we close the database with the db.close() method and finally update the GUI data to the latest state using the self.update() method.

#### Delete from Database

```.py
 def delete_songs(self):
        checked = self.data_table.get_row_checks()
        Logger.info("Deleting vocabulary from database...")
        try:
            for row in checked:
                vocab_id = int(row[0])
                query = f"DELETE FROM songs WHERE id = {vocab_id}"
                db = database_worker("project3_db.db")
                db.run_save(query)
                db.close()
            self.update()
            deletedialog = MDDialog(
                title="Success",
                text="Song deleted successfully",
                size_hint=(0.8, 0.3),
                buttons=[
                    MDFlatButton(
                        text="OK",
                        on_press=lambda x: deletedialog.dismiss()
                    )
                ]
            )
            deletedialog.open()
        except Exception as e:
            Logger.error(f"Error deleting song: {e}")  
```
This program provides a function to remove from the database the songs selected by the user in the data table.

First, it uses the get_row_checks() function to identify the rows selected by the user and obtains a list of the rows selected in the data table. Then, a for loop is used to obtain the ID of the row for each selected row, and an SQL query is generated to remove the selected rows from the database.

The database operation is performed using the database_worker class. Then, after the deletion, the table is updated so that the deleted rows disappear from the data table. If the deletion is successful, a dialog box is displayed using the MDDialog widget to notify the user that the deletion was successful. If an error occurs, an error message is output to the log.

### Search System
```.py
    def search_songs(self):
        search = self.ids.search.text
        db = database_worker("project3_db.db")
        query = "SELECT * from songs where song_title like '%"+search+"%' or artist_name like '%"+search+"%' or genre like '%"+search+"%'"
        result = db.search(query)
        db.close()
        self.data_table.update_row_data(None, result)
  ```
 This code defines a function called "search_songs" that extracts a search query string from a text input field using its corresponding id. The search query string is then used to construct an SQL query for selecting all songs from a database table that contain the search query string in the song title, artist name, or genre fields. The resulting data is fetched from the database using the "db.search" method and saved in the "result" variable. The database connection is then closed using the "db.close" method. Finally, the data table is updated using the "self.data_table.update_row_data(None, result)" method to display the filtered search results. This functionality enables the user to search for and view specific songs based on their song title, artist name, or genre, making it easier to navigate and manage a large database of songs.
 
 
# Criteria D: Functionality

## Appendi
![](pic_jpg.png)
This is proof of client approval of proposed Success Criteria

## Citations
1.Luna, J. C. (2022, January 21). Top programming languages for Data Scientists in 2022. DataCamp. Retrieved March 10, 2023, from https://www.datacamp.com/blog/top-programming-languages-for-data-scientists-in-2022 
2.Advantages of OOP: Explore the top 9 advantages of OOP. EDUCBA. (2022, June 23). Retrieved March 10, 2023, from https://www.educba.com/advantages-of-oop/ 
3.KIVY: Cross-platform Python Framework for nui. Cross-platform Python Framework for GUI apps Development. (n.d.). Retrieved March 10, 2023, from https://kivy.org/ 
4.The Python SQL Toolkit and Object Relational Mapper. SQLAlchemy. (n.d.). Retrieved March 10, 2023, from https://www.sqlalchemy.org/ 
5.Introduction to SQL. SQL Introduction. (n.d.). Retrieved March 10, 2023, from https://www.w3schools.com/sql/sql_intro.asp 
6.Top 2% extraordinary talent on demand™. Talentopia. (n.d.). Retrieved March 10, 2023, from https://www.talentopia.com/ 

## Demonstration Video
https://youtu.be/5navJ4zjRzw
