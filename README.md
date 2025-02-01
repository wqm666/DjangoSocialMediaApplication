# Django Social Media Application

Welcome to my Django Social Media Platform! Connect with others, share content, and explore exciting features.

[![Site Preview](static/img/logo.png)](https://djangosocialmediaapplication.pythonanywhere.com/users/profile/1/)

## Live Demo
Check out the live demo: [Social Media Platform Demo](https://djangosocialmediaapplication.pythonanywhere.com)

## Features

- **Authentication**: Securely sign up, sign in, and reset passwords.
- **Profiles**: Explore, view, edit, and delete user profiles.
- **Posting**: Create, edit, and delete posts. Attach images for a rich experience.
- **Comments**: Engage with posts through comments.
- **Likes**: Express your appreciation by liking posts and comments.
- **Saves**: Easily find the posts you need by saving posts
- **Follow/Unfollow**: Stay updated with others' posts.
- **Search**: Easily find users.
- **Email Verification**: Ensure account security.

> [!IMPORTANT]
> If you're unable to log in, make sure to enter your email information in the .env file.

## Repository

Explore the source code and contribute to the development on GitHub:

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-blue?logo=github)](https://github.com/DevOgabek/DjangoSocialMediaApplication)

## Installation

Follow these steps to set up the Social Media Platform on your local machine:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/DevOgabek/DjangoSocialMediaApplication.git
   ```

2. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variables**:
   - Create a `.env` file in the root directory.
   - Define the following environment variables:
     - `EMAIL`: Your Gmail email address for sending verification emails.
     - `PASSWORD`: Your Gmail password or an application-specific password for sending emails.

4. **Apply database migrations**:

   ```bash
   python manage.py migrate
   ```

5. **Run the development server**:

   ```bash
   python manage.py runserver
   ```

After completing these steps, you'll have the Social Media Platform up and running locally. Access it via your web browser at `http://localhost:8000`.

## Usage

1. **Sign Up / Sign In**: Create an account or sign in.
2. **Profile Management**: Customize profile settings.
3. **Posting Content**: Share thoughts and multimedia.
4. **Interacting with Content**: Like, comment, and share.
5. **Discovering Content**: Find users and explore posts.
6. **Account Settings**: Manage security and privacy.

## Contributing

Contributions welcome! Open issues or submit pull requests.

> [!IMPORTANT]
> When creating an account, ensure you enter a valid email address. You'll need to confirm it when logging in.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


> [!IMPORTANT]
> If you're unable to log in, make sure to enter your email information in the .env file. Also, feel free to explore the source code and contribute to the development on [GitHub](https://github.com/DevOgabek/DjangoSocialMediaApplication).

```
DjangoSocialMediaApplication
├─ .git
│  ├─ config
│  ├─ description
│  ├─ HEAD
│  ├─ hooks
│  │  ├─ applypatch-msg.sample
│  │  ├─ commit-msg.sample
│  │  ├─ fsmonitor-watchman.sample
│  │  ├─ post-update.sample
│  │  ├─ pre-applypatch.sample
│  │  ├─ pre-commit.sample
│  │  ├─ pre-merge-commit.sample
│  │  ├─ pre-push.sample
│  │  ├─ pre-rebase.sample
│  │  ├─ pre-receive.sample
│  │  ├─ prepare-commit-msg.sample
│  │  ├─ push-to-checkout.sample
│  │  ├─ sendemail-validate.sample
│  │  └─ update.sample
│  ├─ index
│  ├─ info
│  │  └─ exclude
│  ├─ logs
│  │  ├─ HEAD
│  │  └─ refs
│  │     ├─ heads
│  │     │  └─ main
│  │     └─ remotes
│  │        └─ origin
│  │           └─ HEAD
│  ├─ objects
│  │  ├─ info
│  │  └─ pack
│  │     ├─ pack-04695f2ef92bb3e6784c9298b994eb712cf7fe10.idx
│  │     ├─ pack-04695f2ef92bb3e6784c9298b994eb712cf7fe10.pack
│  │     └─ pack-04695f2ef92bb3e6784c9298b994eb712cf7fe10.rev
│  ├─ packed-refs
│  └─ refs
│     ├─ heads
│     │  └─ main
│     ├─ remotes
│     │  └─ origin
│     │     └─ HEAD
│     └─ tags
├─ .gitignore
├─ config
│  ├─ asgi.py
│  ├─ settings.py
│  ├─ urls.py
│  ├─ wsgi.py
│  ├─ __init__.py
│  └─ __pycache__
│     ├─ settings.cpython-310.pyc
│     ├─ settings.cpython-312.pyc
│     ├─ urls.cpython-310.pyc
│     ├─ urls.cpython-312.pyc
│     ├─ wsgi.cpython-310.pyc
│     ├─ wsgi.cpython-312.pyc
│     ├─ __init__.cpython-310.pyc
│     └─ __init__.cpython-312.pyc
├─ db.sqlite3
├─ interactions
│  ├─ admin.py
│  ├─ apps.py
│  ├─ migrations
│  │  ├─ 0001_initial.py
│  │  ├─ 0002_remove_save_post_remove_save_user_post_saved_by_and_more.py
│  │  ├─ 0003_alter_post_post_img.py
│  │  ├─ __init__.py
│  │  └─ __pycache__
│  │     ├─ 0001_initial.cpython-310.pyc
│  │     ├─ 0001_initial.cpython-312.pyc
│  │     ├─ 0002_remove_save_post_remove_save_user_post_saved_by_and_more.cpython-310.pyc
│  │     ├─ 0002_remove_save_post_remove_save_user_post_saved_by_and_more.cpython-312.pyc
│  │     ├─ 0003_alter_post_post_img.cpython-310.pyc
│  │     ├─ 0003_alter_post_post_img.cpython-312.pyc
│  │     ├─ __init__.cpython-310.pyc
│  │     └─ __init__.cpython-312.pyc
│  ├─ models.py
│  ├─ tests.py
│  ├─ urls.py
│  ├─ views.py
│  ├─ __init__.py
│  └─ __pycache__
│     ├─ admin.cpython-310.pyc
│     ├─ admin.cpython-312.pyc
│     ├─ apps.cpython-310.pyc
│     ├─ apps.cpython-312.pyc
│     ├─ models.cpython-310.pyc
│     ├─ models.cpython-312.pyc
│     ├─ urls.cpython-310.pyc
│     ├─ urls.cpython-312.pyc
│     ├─ views.cpython-310.pyc
│     ├─ views.cpython-312.pyc
│     ├─ __init__.cpython-310.pyc
│     └─ __init__.cpython-312.pyc
├─ LICENSE
├─ manage.py
├─ media
│  ├─ post_images
│  │  ├─ 159776741.gif.png
│  │  └─ 73b3-ireifzh4788168.jpg
│  ├─ post_img.jpg
│  ├─ profile_images
│  │  └─ 159776741.gif.png
│  └─ profile_img.jpeg
├─ README.md
├─ requirements.txt
├─ static
│  ├─ css
│  │  ├─ comments.css
│  │  ├─ create.css
│  │  ├─ email_body.css
│  │  ├─ message.css
│  │  ├─ nav.css
│  │  ├─ post.css
│  │  ├─ profile.css
│  │  ├─ registrations
│  │  │  └─ style.css
│  │  ├─ search.css
│  │  └─ settings.css
│  ├─ img
│  │  └─ logo.png
│  └─ js
│     ├─ comments.js
│     ├─ create.js
│     ├─ message.js
│     ├─ post.js
│     ├─ profile.js
│     ├─ search.js
│     ├─ settings.js
│     └─ verification.js
├─ template
│  ├─ base.html
│  ├─ create.html
│  ├─ edit.html
│  ├─ email
│  │  └─ email_body.html
│  ├─ home.html
│  ├─ my_profile.html
│  ├─ profile.html
│  ├─ registrations
│  │  ├─ change_password.html
│  │  ├─ reset_password.html
│  │  ├─ signin.html
│  │  ├─ signup.html
│  │  └─ verification.html
│  ├─ save.html
│  ├─ search.html
│  └─ settings.html
└─ users
   ├─ admin.py
   ├─ apps.py
   ├─ management
   │  └─ commands
   │     ├─ create_demo_users.py
   │     └─ __pycache__
   │        ├─ create_demo_users.cpython-312.pyc
   │        ├─ create_demo_users_1.cpython-312.pyc
   │        ├─ create_demo_users_2.cpython-312.pyc
   │        └─ create_demo_users_3.cpython-312.pyc
   ├─ migrations
   │  ├─ 0001_initial.py
   │  ├─ 0002_remove_profile_viewed_posts.py
   │  ├─ __init__.py
   │  └─ __pycache__
   │     ├─ 0001_initial.cpython-310.pyc
   │     ├─ 0001_initial.cpython-312.pyc
   │     ├─ 0002_remove_profile_viewed_posts.cpython-310.pyc
   │     ├─ 0002_remove_profile_viewed_posts.cpython-312.pyc
   │     ├─ __init__.cpython-310.pyc
   │     └─ __init__.cpython-312.pyc
   ├─ models.py
   ├─ tasks.py
   ├─ tests.py
   ├─ urls.py
   ├─ views.py
   ├─ __init__.py
   └─ __pycache__
      ├─ admin.cpython-310.pyc
      ├─ admin.cpython-312.pyc
      ├─ apps.cpython-310.pyc
      ├─ apps.cpython-312.pyc
      ├─ models.cpython-310.pyc
      ├─ models.cpython-312.pyc
      ├─ urls.cpython-310.pyc
      ├─ urls.cpython-312.pyc
      ├─ views.cpython-310.pyc
      ├─ views.cpython-312.pyc
      ├─ __init__.cpython-310.pyc
      └─ __init__.cpython-312.pyc

```