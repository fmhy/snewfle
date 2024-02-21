## snewfle

🎠 Typed Reddit API wrapper

## Matrix

See [reddit.com/dev/api](https://www.reddit.com/dev/api/)

### account

- [ ] /api/v1/me/blocked - 404 error
- [ ] /api/v1/me
- [ ] /api/v1/me/karma
- [ ] /api/v1/me/prefs
- [ ] /api/v1/me/trophies
- [ ] /prefs/blocked
- [ ] /api/v1/me/friends
- [ ] /prefs/friends - same functionality as /api/v1/me/friends, just different response format
- [ ] /prefs/messaging
- [ ] /prefs/trusted

### captcha

- [ ] /api/needs_captcha

### collections

- [ ] /api/v1/collections/add_post_to_collection
- [ ] /api/v1/collections/collection
- [ ] /api/v1/collections/create_collection
- [ ] /api/v1/collections/delete_collection
- [ ] /api/v1/collections/follow_collection
- [ ] /api/v1/collections/remove_post_in_collection
- [ ] /api/v1/collections/reorder_collection
- [ ] /api/v1/collections/subreddit_collections
- [ ] /api/v1/collections/update_collection_description
- [ ] /api/v1/collections/update_collection_display_layout
- [ ] /api/v1/collections/update_collection_title

### emoji

- [ ] /api/v1/subreddit/emoji.json
- [ ] /api/v1/subreddit/emoji/emoji_name
- [ ] /api/v1/subreddit/emoji_asset_upload_s3.json
- [ ] /api/v1/subreddit/emoji_custom_size
- [ ] /api/v1/subreddit/emojis/all

### flair

- [ ] /api/clearflairtemplates
- [ ] /api/deleteflair
- [ ] /api/deleteflairtemplate
- [ ] /api/flair
- [ ] /api/flair_template_order
- [ ] /api/flairconfig
- [ ] /api/flaircsv
- [ ] /api/flairlist
- [ ] /api/flairselector
- [ ] /api/flairtemplate
- [ ] /api/flairtemplate_v2
- [ ] /api/link_flair
- [ ] /api/link_flair_v2
- [ ] /api/selectflair
- [ ] /api/setflairenabled
- [ ] /api/user_flair
- [ ] /api/user_flair_v2

### reddit gold

- [ ] /api/v1/gold/gild/fullname
- [ ] /api/v1/gold/give/username

### links & comments

- [ ] /api/comment
- [ ] /api/del
- [ ] /api/editusertext
- [ ] /api/event_post_time
- [ ] /api/follow_post
- [ ] /api/hide
- [ ] /api/info
- [ ] /api/lock
- [ ] /api/marknsfw
- [ ] /api/morechildren
- [ ] /api/report
- [ ] /api/report_award
- [ ] /api/save
- [ ] /api/saved_categories
- [ ] /api/sendreplies
- [ ] /api/set_contest_mode
- [ ] /api/set_subreddit_sticky
- [ ] /api/set_suggested_sort
- [ ] /api/spoiler
- [ ] /api/store_visits
- [ ] /api/submit
- [ ] /api/unhide
- [ ] /api/unlock
- [ ] /api/unmarknsfw
- [ ] /api/unsave
- [ ] /api/unspoiler
- [ ] /api/vote

### listings

- [ ] /best
- [ ] /by_id/names
- [ ] /comments/article
- [ ] /controversial
- [ ] /duplicates/article
- [ ] /hot
- [ ] /new
- [ ] /random
- [ ] /rising
- [ ] /top
- [ ] /sort

### live threads

- [ ] /api/live/by_id/names
- [ ] /api/live/create
- [ ] /api/live/happening_now
- [ ] /api/live/thread/accept_contributor_invite
- [ ] /api/live/thread/close_thread
- [ ] /api/live/thread/delete_update
- [ ] /api/live/thread/edit
- [ ] /api/live/thread/hide_discussion
- [ ] /api/live/thread/invite_contributor
- [ ] /api/live/thread/leave_contributor
- [ ] /api/live/thread/report
- [ ] /api/live/thread/rm_contributor
- [ ] /api/live/thread/rm_contributor_invite
- [ ] /api/live/thread/set_contributor_permissions
- [ ] /api/live/thread/strike_update
- [ ] /api/live/thread/unhide_discussion
- [ ] /api/live/thread/update
- [ ] /live/thread
- [ ] /live/thread/about
- [ ] /live/thread/contributors
- [ ] /live/thread/discussions
- [ ] /live/thread/updates/update_id

### private messages

- [ ] /api/block
- [ ] /api/collapse_message
- [ ] /api/compose
- [ ] /api/del_msg
- [ ] /api/read_all_messages
- [ ] /api/read_message
- [ ] /api/unblock_subreddit
- [ ] /api/uncollapse_message
- [ ] /api/unread_message
- [ ] /message/inbox
- [ ] /message/sent
- [ ] /message/unread
- [ ] /message/where

### misc

- [ ] /api/saved_media_text
- [ ] /api/v1/scopes

### moderation

- [ ] /about/edited
- [ ] /about/log
- [ ] /about/modqueue
- [ ] /about/reports
- [ ] /about/spam
- [ ] /about/unmoderated
- [ ] /about/location
- [ ] /api/accept_moderator_invite
- [ ] /api/approve
- [ ] /api/distinguish
- [ ] /api/ignore_reports
- [ ] /api/leavecontributor
- [ ] /api/leavemoderator
- [ ] /api/mute_message_author
- [ ] /api/remove
- [ ] /api/show_comment
- [ ] /api/snooze_reports
- [ ] /api/unignore_reports
- [ ] /api/unmute_message_author
- [ ] /api/unsnooze_reports
- [ ] /api/update_crowd_control_level
- [ ] /stylesheet

### new modmail

- [ ] /api/mod/bulk_read
- [ ] /api/mod/conversations
- [ ] /api/mod/conversations/:conversation_id
- [ ] /api/mod/conversations/:conversation_id/approve
- [ ] /api/mod/conversations/:conversation_id/archive
- [ ] /api/mod/conversations/:conversation_id/disapprove
- [ ] /api/mod/conversations/:conversation_id/highlight
- [ ] /api/mod/conversations/:conversation_id/mute
- [ ] /api/mod/conversations/:conversation_id/temp_ban
- [ ] /api/mod/conversations/:conversation_id/unarchive
- [ ] /api/mod/conversations/:conversation_id/unban
- [ ] /api/mod/conversations/:conversation_id/unmute
- [ ] /api/mod/conversations/:conversation_id/user
- [ ] /api/mod/conversations/read
- [ ] /api/mod/conversations/subreddits
- [ ] /api/mod/conversations/unread
- [ ] /api/mod/conversations/unread/count

### modnote

- [ ] /api/mod/notes
- [ ] /api/mod/notes/recent

### multis

- [ ] /api/filter/filterpath
- [ ] /api/filter/filterpath/r/srname
- [ ] /api/multi/copy
- [ ] /api/multi/mine
- [ ] /api/multi/user/username
- [ ] /api/multi/multipath
- [ ] /api/multi/multipath/description
- [ ] /api/multi/multipath/r/srname

### search

- [ ] /search

### subreddits

- [ ] /about/banned
- [ ] /about/contributors
- [ ] /about/moderators
- [ ] /about/muted
- [ ] /about/wikibanned
- [ ] /about/wikicontributors
- [ ] /about/where
- [ ] /api/delete_sr_banner
- [ ] /api/delete_sr_header
- [ ] /api/delete_sr_icon
- [ ] /api/delete_sr_img
- [ ] /api/recommend/sr/srnames
- [ ] /api/search_reddit_names
- [ ] /api/search_subreddits
- [ ] /api/site_admin
- [ ] /api/submit_text
- [ ] /api/subreddit_autocomplete
- [ ] /api/subreddit_autocomplete_v2
- [ ] /api/subreddit_stylesheet
- [ ] /api/subscribe
- [ ] /api/upload_sr_img
- [ ] /api/v1/subreddit/post_requirements
- [ ] /r/subreddit/about
- [ ] /r/subreddit/about/edit
- [ ] /r/subreddit/about/rules
- [ ] /r/subreddit/about/traffic
- [ ] /sidebar
- [ ] /sticky
- [ ] /subreddits/default
- [ ] /subreddits/gold
- [ ] /subreddits/mine/contributor
- [ ] /subreddits/mine/moderator
- [ ] /subreddits/mine/streams
- [ ] /subreddits/mine/subscriber
- [ ] /subreddits/mine/where
- [ ] /subreddits/new
- [ ] /subreddits/popular
- [ ] /subreddits/search
- [ ] /subreddits/where
- [ ] /users/new
- [ ] /users/popular
- [ ] /users/search
- [ ] /users/where

### users

- [ ] /api/block_user
- [ ] /api/friend
- [ ] /api/report_user
- [ ] /api/setpermissions
- [ ] /api/unfriend
- [ ] /api/user_data_by_account_ids
- [ ] /api/username_available
- [ ] /api/v1/me/friends/username
- [ ] /api/v1/user/username/trophies
- [ ] /user/username/about
- [ ] /user/username/comments
- [ ] /user/username/downvoted
- [ ] /user/username/gilded
- [ ] /user/username/hidden
- [ ] /user/username/overview
- [ ] /user/username/saved
- [ ] /user/username/submitted
- [ ] /user/username/upvoted
- [ ] /user/username/where

### widgets

- [ ] /api/widget
- [ ] /api/widget/widget_id
- [ ] /api/widget_image_upload_s3
- [ ] /api/widget_order/section
- [ ] /api/widgets

### wiki

- [ ] /api/wiki/alloweditor/add
- [ ] /api/wiki/alloweditor/del
- [ ] /api/wiki/alloweditor/act
- [ ] /api/wiki/edit
- [ ] /api/wiki/hide
- [ ] /api/wiki/revert
- [ ] /wiki/discussions/page
- [ ] /wiki/pages
- [ ] /wiki/revisions
- [ ] /wiki/revisions/page
- [ ] /wiki/settings/page
- [ ] /wiki/page
