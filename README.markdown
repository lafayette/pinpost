## PinPost
Hook for IPB 3.2 and greater that allows you to pin first posts in the selected forums.

## Configuration
Install hook from ACP by importing hook XML and insert in conf_global.php such line:
$INFO['pin_topic_forums'] = array(1,2,3);
where 1,2,3 - forum IDs where we need to pin first posts.