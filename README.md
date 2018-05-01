# Replace-Gravatar-By-QQ-Avatar
Replace the Gravatar by QQ avatar (if the author uses QQ mail) for those who do not have a Gravatar, and cache all the avatars. 

### Usage
1. Place "default.jpg" under the path: ABSPATH . 'avatar/' (This is also the location of the cache).
2. Add the content between "&lt;?php" and "?&gt;" of avatar_wget.php to "functions.php" of your theme.

### Note
Please make sure that exec() is enabled, and wget is installed.
