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

| Task No | Planned Action                                            | Planned Outcome                                                                                                     | Time estimate | Target completion date | Criterion |
|---------|-----------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|---------------|------------------------|-----------|
| 1       | Planning: First Meeting with client                       | Start collecting the context of the problem and research on current solutions                                       | 3min          | Mar 28                 | A         |
| 2       | Planning: Defining problem and proposed solution          | Start on refining client's requirements and tools needed                                                            | 2 hr          | Mar 29                 | A         |
| 3       | Initializing codebase                                     | To have the base environment of program ready for coding                                                            | 1 hr          | Mar 29                 | B         |
| 4       | Planning : Second Meeting with client                     | Decided success criteria(See Appendix 2)                                                                            | 5 min         | Mar 30                 | A         |
| 5       | Planning: Creating Wireframe                              | To have Wireframe diagram finished                                                                                  | 1 hr          | Apr 1                  | B         |
| 6       | Development: Coding the structure of the database         | Finalize on the structure of the database                                                                           | 10min         | Apr 2                  | C         |
| 7       | Development: Initializing db_manager                      | To have a base for the database handler coded and ready for new functions to be coded on top                        | 10min         | Apr 2                  | C         |
| 8       | Development: Coding basic endpoints                       | To have basic endpoint coded                                                                                        | 15min         | Apr 2                  | C         |
| 9       | Development: Coding the token manager                     | To have the JWT system implement as a base for my flask application                                                 | 45min         | Apr 2                  | C         |
| 10      | Development: Coding the Login/Registration  backend       | To have the backend database logics implemented for the user management                                             | 20min         | Apr 3                  | C         |
| 11      | Development: Coding the login page                        | To design the login page for the website, complete with the registration function as well                           | 1hr           | Apr 3                  | C         |
| 12      | Development: Coding Header/Footer                         | To have the header/footer of the website designed and coded                                                         | 20min         | Apr 4                  | C         |
| 13      | Development: Coding Dashboard                             | To have the layout of the dashboard page coded                                                                      | 30min         | Apr 4                  | C         |
| 14      | Development: Coding New Post                              | To have the layout of the new post page coded                                                                       | 30min         | Apr 5                  | C         |
| 15      | Development: Coding My Profile                            | To have the layout of the my profile page coded                                                                     | 30min         | Apr 5                  | C         |
| 16      | Development: Coding logic for Dashboard                   | To have the dashboard page connected to the database logic                                                          | 45min         | Apr 6                  | C         |
| 17      | Development: Coding logic for New Post                    | To have the new post page connected to the database logic                                                           | 45min         | Apr 7                  | C         |
| 18      | Development: Coding logic for My Profile                  | To have the my profile page connected to the database logic                                                         | 45min         | Apr 8                  | C         |
| 19      | Development: Coding the Syntax Highlighting for code      | To have the plugin for syntax highlighting code implemented properly                                                | 1hr           | Apr
| 20      | Development: Coding the logic for "other" code languages  | To have the function for other code language other than the listed one to be catered for                            | 20min         | Apr 9                  | C         |
| 21      | Development: Coding Rating System                         | To have the the like and dislike button connect with the backend database                                           | 30min         | Apr 10                 | C         |
| 22      | Development: Coding Changing Password                     | To have the change passwords function coded                                                                         | 15min         | Apr 11                 | C         |
| 23      | Implementation: Beta Testing                              | To have feedback from client to know how to improve                                                                 | 1hr           | Apr 11                 | C         |
| 24      | Development: Coding Delete Confirmation                   | To have the feedback from client's beta testing implemented                                                         | 15min         | Apr 11                 | C         |
| 25      | Development: Consolidating Code into `base.html` | To reduce repetitive code and centralize the dependencies for the website                                           | 1hr           | Apr 12                 | C         |
| 26      | Planning: Creating System Diagram                         | To have understanding of the computer systems required for the completing the success criteria                      | 30min         | Apr 13                 | B         |
| 27      | Planning: Creating UML Diagram                            | To have understanding of the different parts of the code                                                            | 30min         | Apr 13                 | B         |
| 28      | Planning: Creating ER Diagram                             | To have the structure of the database documented                                                                    | 30min         | Apr 13                 | B         |
| 29      | Planning: Creating Flow Diagrams                          | To have a clear understanding of difficult parts of code                                                            | 1hr           | Apr 14                 | B         |
| 30      | Development: Cleaning up Code                             | To have the code finalized and organized for easy-understanding                                                     | 10min         | Apr 16                 | C         |
| 31      | Planning: Creating Test Plan                              | To have a test plan created for confirming if the application works to standard                                     | 30min         | Apr 16                 | B         |
| 32      | Implementation: Evaluation by client                      | To have the website evaluated by the client and the subsequent evidence documented                                  | 1hr           | Apr 19                 | E         |
| 33      | Beta Testing: Evaluation by peer                          | To have the website evaluated by a peer and the subsequent evidence documented                                      | 1hr           | Apr 19                 | E         |
| 34      | Implementation: Collect Recommendations from users/client | To have taken in recommendations from both evaluations on how the website can be improved and document them properly | 15min         | Apr 19                 | E         |
| 35      | Development: Implementing recommendations                  | To have the recommendations implemented properly                                                                    | 1hr           | Apr 21                 | C         |
| 36      | Implementation: Finalizing Documentation                  | To have the final documentations made and the project ready for submission                                          | 2hr           | Apr 25                 | D         |
| 37      | Testing: Final Testing and Debugging                       | To have the final testing conducted on the website and all errors removed                                           | 1hr           | Apr 25                 | D         |
| 38      | Test: Integration testing                            | To test the integration between various modules and functionalities of the application to ensure they work together | 2hrs          | May 4                  | D         |
| 39      | Test: User acceptance testing                        | To test the application with actual users to ensure that it meets their needs and expectations                       | 4hrs          | May 6                  | D         |
| 40      | Implementation: Deployment                           | To deploy the application on the production server for public use                                                    | 2hrs          | May 7                  | E         |
| 41      | Implementation: User training                        | To provide training for users on how to use the application effectively                                               | 3hrs          | May 8                  | E         |
| 42      | Test: Performance testing                            | To test the application's performance under various loads and stress conditions to ensure it can handle high traffic  | 3hrs          | May 9                  | D         |
| 43      | Test: Security testing                               | To test the application's security features to ensure that sensitive data is protected from unauthorized access         | 2hrs          | May 9                  | D         |
| 44      | Implementation: User documentation                   | To create documentation for users on how to use the application and troubleshoot common issues                        | 4hrs          | May 10                 | E         |
| 45      | Implementation: Final revisions                      | To make any final revisions or improvements to the application based on feedback from testing and user evaluation     | 3hrs          | May 10                 | E         |
| 46      | Implementation: Final deployment                      | To deploy the final version of the application on the production server for public use                                | 1hr           | May 10                 | E         |
## Flow Diagrams


## Test Plan

Test Plan

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
| Software/Development Tools | Coding Structure Tools          | Libraries      |
|----------------------------|---------------------------------|----------------|
| PyCharm                    |Encryption                       | Flask          |
| Relational databases       | Objects, attributes and methods | sqlite3        |
| SQLite                     | If statements                   | passlib        |
| Python                     |                                 |                |
| Chat GPT                   |                                 |                | 

## List of techniques used
1. Flask library/routes
2. For loops
3. If statements
4. Password hashing
5.Object Relation Mapping(ORM): SQLAlchemy
6. Lists
7. Cookies
8. Object-Oriented Programming(OOP)



## Development

## Success criteria 1 

To achieve the success criterion of allowing users to post on the website, I divided the process into three sections: getting information from the UI, validating it, and uploading it to the database. The code for this process is shown below:

```python
@app.route('/new_post', methods=['GET','POST'])
def new_post():
    msg = ""
    if request.cookies.get('user_id'): # Check if user is logged in (For security purposes)
        user_id = request.cookies.get('user_id') # To track whose post this is
        db = database_worker("social_net.db")
        if request.method == 'POST':
            title = request.form['title']
            content = request.form['content']
            ingredients = request.form['ingredients']
            if len(title) > 0 and len(content) > 0 and len(ingredients)>0: # Validate that the user is not posting an empty post
                new_post = f"INSERT into posts (title, content, ingredients, user_id) values('{title}','{content}','{ingredients}',{user_id})"
                db.run_save(query=new_post)
                posts = db.search("Select * FROM posts")
                return redirect(url_for('home', posts = posts )) # Redirect to home page
            else:
                msg = "Please enter title, content and ingredients" # Error message is displayed in the UI
                return render_template("post.html", message=msg)
        return render_template("post.html", message=msg)
    else:
        return redirect('post.html')
```

To ensure that unauthorized access is prevented, I validated the user by checking if they were logged in before allowing them to access the post page. If the user was authenticated and the form was posted, I retrieved the information from the UI and validated it. After validation, I connected to the database using the `database_worker` function, then inserted the post into the `posts` table. To redirect the user back to the home page with the new post displayed, I used the `database_worker` function again to search for all posts, then redirected the user to the home page using `return redirect(url_for('home', posts = posts ))`.

I made use of the `database_worker` function to simplify my code and demonstrate pattern recognition skills. By creating a function for a repeated task such as connecting to the database, I made the code more readable and easier to maintain. I also made sure to explain the techniques used in my development process, including algorithmic thinking, pattern recognition, abstraction, and decomposition. 

Furthermore, the use of the `database_worker` function and other programming techniques such as input validation, event handlers, and nested control structures helped me to address the scenario identified in criterion A with a moderate level of complexity and ingenuity. I also made use of good coding practices such as keeping the code DRY (Don't Repeat Yourself) and KISS (Keep It Simple, Stupid).

## Success criteria 2

## Success Criteria number 3 and 5
For these 2 success criteria, there were two main issues. First was getting all of the posts from the database, then displaying them in the homepage for the user to see. Then the other problem was that I had to search the database for a specific ingredient and then display only the posts that applied to the statement. The first one was not as challenging, however the second was quite a challenge. 

```.html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>ホーム</title>
  <link rel="stylesheet" href="../static/my_style.css">
  <link rel="stylesheet" href="../static/header.css">
</head>
  <header>
    <div class="logo">
      <img src="/static/icon.png" alt="Logo">
    </div>
    <div class="site-name">
      <h1>みんなのビール</h1>
    </div>
    <nav>
      <ul>
        <li><a href="/home">ホーム</a></li>
        <li><a href="/new_post">投稿</a></li>
        <li><a href="/profile/<user_id>">プロフィール</a></li>
        <li><a href="/login">ログイン</a></li>
        <li><a href="/register">新規登録</a></li>
        <li><a href="/logout">ログアウト</a></li>
      </ul>
    </nav>
  </header>
<body>
  <main>
      {% block content %}{% endblock %}
    <h1>投稿一覧</h1>
    <ul class="post-list">
      <li class="post">
        <img src="path/to/post-image.jpg" alt="投稿イメージ">
        <div class="post-info">
          <h2 class="post-title">投稿タイトル</h2>
          <p class="post-description">投稿の説明文がここに入ります。</p>
          <div class="post-recipe">
            <h3 class="post-recipe-title">レシピ</h3>
            <p class="post-recipe-description">レシピの説明文がここに入ります。</p>
          </div>
        </div>
      </li>
      <!-- 他の投稿をここに追加する -->
    </ul>
  </main>
</body>
  <footer>
    <!-- フッターのHTMLコード -->
  </footer>
</html>

```
This first piece of code is for my HTML. For the HTML, I made sure to create a table that would display everything from the posts page. This enables the user to see other users posts. Additionally I made sure to have at the top of the page a menu bar that would take the users to different pages in the application and there is also a search bar so that the user can search for recipes based on ingredients. Lastly, for each post in the table, the ID is made into a link for the shopping list. Therefore, clicking this will enable the user to create their own shopping list in the application. 

```.py
{% extends 'base.html' %}
{% block content %}

<h1>Home Page</h1>
{% if posts %}
    <form method="post" action="{{ url_for('home') }}">
        <label for="query">Search posts by ingredients:</label>
        <input type="text" name="query">
        <button type="submit">Search</button>
    </form>
    {% for post in posts %}
        <h3>{{ post[1] }}</h3>
        <p>{{ post[2] }}</p>
        <p>{{ post[4] }}</p>
        <p>Posted by {{ post[3] }} </p>
        <hr>
    {% endfor %}
{% endif %}
{% endblock %}



```
The above code is showcasing the home page python code. First I make sure that the user is logged in as this page is restricted to people who have an accout. Then I just use the database_worker function to get all the posts. However, if the user sends a search request, then I don't get all the posts, instead I use the % signs to get posts that are like the search query and then show those on the page. 

## Success criteria number 6
```.py

@app.route('/profile/<user_id>', methods=['GET','POST'])
def profile(user_id:int): #Get the user_id to know which user it is
    if request.cookies.get('user_id'): #Check if user is logged in (For security purposes)
        db = database_worker("social_net.db")
        user,posts = None, None
        user= db.search(f"SELECT * from users where id={user_id}")
        if user:
            posts = db.search(f"select * from posts where user_id={user_id}")
            user = user[0] #remeber db.search returns a list
        return render_template("profile.html", user=user, posts=posts) #Showcases the user name and posts
    else:
        return redirect('login')
	
```
The above code shows the function for the profile page. This enables the user to view information about themselves, which includes their prior posts. To do this I used databases to save their posts and if statmenets to validate if they were users. This would enable me to showcase their posts for which I used the same format as the home method and called it from the database then displayed it. 

```.html
<!DOCTYPE html>
<html>
  <meta charset="UTF-8">
  <title>{% block title %}{% endblock %}</title>
  <link rel="stylesheet" href="../static/my_style.css">
  <link rel="stylesheet" href="../static/header.css">
</head>
<body>
<div>
    <a href = "{{ url_for("home") }}"> Homepage</a>
</div>

{% if user %}
    <h1>Welcome, {{ user[1] }}</h1>
    {% if posts|length > 0 %}
    <p>Your posts are:</p>
    <table>
    <tr>
        <th>id</th>
        <th>Title</th>
        <th>Content</th>
    </tr>
        {# template language jinja2 #}
    {% for p in posts %}
    <tr>
        <td>{{ p[0] }}</td>
        <td>{{ p[1].title() }}</td>
        <td>{{ p[2] }}</td>
    </tr>
    {% endfor %}
    </table>
    {% else %}
        <p>You don't have posts yet</p>
    {% endif %}
{% else %}
<h1> User does not exist</h1>
{% endif %}
</body>
</html>

```
The above code shows my HTML for my profile page. This enables the user to view their own profile, and I coded python in the HTML page so that I could adjust what message appears in the final HTML rendering. This makes the code much simpler as it's not going through the python file and it's in the HTML. 
## Pattern recognition

```.py
from my_lib import database_worker, encrpyt_password, check_password
```
I made this to simplify my code. Creating this function means that every time i have to save something to a database, I am able to just call the function instead of writing it all out every single time. Additionally, if I need to change something I only have one point to change. This is an example of the computational thinking skill pattern recognition as I was able to see that this is something that is repeated throughout. Additionally, it also shows algorithm design as I used an algorithm that enabled me to do the exact same things many times. 

## Base.html
```.html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>ホーム</title>
  <link rel="stylesheet" href="../static/my_style.css">
  <link rel="stylesheet" href="../static/header.css">
</head>
  <header>
    <div class="logo">
      <img src="/static/icon.png" alt="Logo">
    </div>
    <div class="site-name">
      <h1>みんなのビール</h1>
    </div>
    <nav>
      <ul>
        <li><a href="/home">ホーム</a></li>
        <li><a href="/new_post">投稿</a></li>
        <li><a href="/profile/<user_id>">プロフィール</a></li>
        <li><a href="/login">ログイン</a></li>
        <li><a href="/register">新規登録</a></li>
        <li><a href="/logout">ログアウト</a></li>
      </ul>
    </nav>
  </header>
<body>
  <main>
      {% block content %}{% endblock %}
    <h1>投稿一覧</h1>
    <ul class="post-list">
      <li class="post">
        <img src="path/to/post-image.jpg" alt="投稿イメージ">
        <div class="post-info">
          <h2 class="post-title">投稿タイトル</h2>
          <p class="post-description">投稿の説明文がここに入ります。</p>
          <div class="post-recipe">
            <h3 class="post-recipe-title">レシピ</h3>
            <p class="post-recipe-description">レシピの説明文がここに入ります。</p>
          </div>
        </div>
      </li>
      <!-- 他の投稿をここに追加する -->
    </ul>
  </main>
</body>
  <footer>
    <!-- フッターのHTMLコード -->
  </footer>
</html>

```

I made this file as it enabled me to have a common html throughout my website. This enabled me to add a menu bar which I used in a few of my pages. Again, this was to prevent redundant code in my files. I could just have one file that organized the menu bar of a few of my screens instead of writing it in each single one. 

## Register

```.py

    @app.route('/register', methods = ["GET", "POST"])
def register():
    msg = ""
    if request.method == 'POST':
        email = request.form['email']
        username = request.form['username']
        passwd = request.form['passwd']
        passwd_check = request.form['passwd_check']
        if passwd != passwd_check:
            msg = "Passwords do not match."
        else:
            db = database_worker("social_net.db")
            existing_user = db.search(f"SELECT * from users where email = '{email}'")
            if existing_user:
                msg = "User already exists."
            else:
                query = f"INSERT into users (email, username, password) values ('{email}', '{username}', '{encrpyt_password(passwd)}')"
                db.run_save(query=query)
                db.close()
                return redirect(url_for('login'))
    return render_template('register.html', message=msg)

```
    
   In this route I used the database worker function to save the users details to the database. I first checked if the method was a post method and then from there I started the process of saving it to the database. I first got the user inputs from the webpage and then from there I made sure to validate them. The email is automatically validated but I made sure that the password was correct by having a confirmation. If it didn’t go through the page would display a message saying that and if it did the user would be redirected to the login. 
   
## User validation

```.py
if request.cookies.get('user_id'):
```
For each web route, I made sure to request the cookies from the user. This made sure that the user was already logged in and has a cookie. This means that even if someone knows the url of the website and they input the url into their search bar,they are not able to access it. This increases the security of the whole website as people need to have had accounts made and have to login as normal.

 ## My_style.css

```.css
body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
}

h1 {
    text-align: center;
}

form {
    margin: auto;
    width: 50%;
    padding: 20px;
    border: 1px solid #ccc;
}

label {
    display: inline-block;
    width: 100px;
    text-align: right;
    margin-right: 10px;
}

input[type="text"],
input[type="password"] {
    width: 200px;
    margin-bottom: 10px;
}

input[type="submit"] {
    display: block;
    margin: auto;
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

input[type="submit"]:hover {
    background-color: #3e8e41;
}

* {
  box-sizing: border-box;
}

body {
  margin: 0;
  padding: 0;
  font-family: sans-serif;
}

/* ヘッダーのスタイル */
header {
  background-color: #fff;
  border-bottom: 1px solid #ddd;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 10px 20px;
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  z-index: 100;
}

.logo img {
  max-height: 60px;
}

.site-name h1 {
  margin: 0;
  font-size: 24px;
  font-weight: bold;
}

nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
}

nav li {
  margin-left: 20px;
}

nav a {
  color: #333;
  text-decoration: none;
  font-size: 16px;
}

nav a:hover {
  color: #000;
}

/* 投稿一覧のスタイル */
.post-list {
  display: flex;
  flex-wrap: wrap;
  margin: 80px auto;
  max-width: 800px;
  padding: 0;
  list-style: none;
}

.post {
  margin: 10px;
  padding: 10px;
  width: calc(33.33% - 20px);
  background-color: #fff;
  box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.1);
}

.post img {
  width: 100%;
  height: auto;
}

.post-info {
  padding: 10px;
}

.post-title {
  margin: 0;
  font-size: 18px;
  font-weight: bold;
}

.post-description {
  margin: 10px 0;
  font-size: 14px;
  color: #888;
}

.post-recipe-title {
  margin: 10px 0;
  font-size: 16px;
  font-weight: bold;
}

.post-recipe-description {
  margin: 0;
  font-size: 14px;
}

/* フォーム全体のスタイル */
form {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 50px;
  font-size: 18px;
}

/* 各inputのスタイル */
input {
  padding: 8px 16px;
  border-radius: 5px;
  border: 1px solid #ccc;
  margin-bottom: 16px;
  width: 100%;
  max-width: 400px;
  box-sizing: border-box;
}

/* ラベルのスタイル */
label {
  margin-right: 16px;
}

/* ボタンのスタイル */
input[type="submit"] {
  background-color: #0095f6;
  color: white;
  font-weight: bold;
  border: none;
  border-radius: 5px;
  padding: 8px 16px;
  cursor: pointer;
}

/* ボタンを押したときのスタイル */
input[type="submit"]:active {
  background-color: #0078d7;
}

/* メッセージのスタイル */
p {
  color: red;
  margin-bottom: 16px;
  text-align: center;
  font-size: 14px;
}

.post-card {
  background-color: #fff;
  border: 1px solid #dbdbdb;
  border-radius: 3px;
  margin-bottom: 30px;
  padding: 20px;
}

.post-card .title {
  font-size: 1.2rem;
  font-weight: 600;
  margin-bottom: 10px;
}

.post-card .content {
  margin-bottom: 10px;
}

.post-card .ingredients {
  font-weight: 500;
  margin-bottom: 10px;
}

.post-card .user {
  color: #8e8e8e;
  font-size: 0.9rem;
}

.post-card .like-count {
  color: #8e8e8e;
  font-size: 0.9rem;
}

.post-card .like-btn {
  background-color: transparent;
  border: none;
  color: #8e8e8e;
  cursor: pointer;
  font-size: 1rem;
  margin-left: 10px;
  padding: 0;
}

.post-card .like-btn:hover {
  color: #ed4956;
}

.post-card .like-btn:focus {
  outline: none;
}

.post-card .comment-btn {
  background-color: transparent;
  border: none;
  color: #8e8e8e;
  cursor: pointer;
  font-size: 1rem;
  padding: 0;
}

.post-card .comment-btn:hover {
  color: #3897f0;
}

.post-card .comment-btn:focus {
  outline: none;
}

.post-card .comments {
  margin-top: 10px;
}

.post-card .comment {
  margin-bottom: 5px;
}

.post-card .comment .user {
  color: #262626;
  font-weight: 600;
}

.post-card .comment .content {
  color: #262626;
}


```
This is the CSS file for my home page. For each file, I made sure to use the same background image and the same style as this one. However, as different pages were made to do different things, I made seperate CSS files for each one, ending up with 3. One for the login and all the other form pages, one for the home page, and one for the shopping list page. This made the CSS as simple as possible without compromising on each pages needs.
 
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
