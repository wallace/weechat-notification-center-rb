Derived from https://github.com/tinifni/gntp-notify

Installation 
------------

Weechat must be built with the ruby option enabled.  If using homebrew

    $ brew install weechat --with-ruby
    
Then, make sure to use *system ruby*

    # using *system ruby*
    $ sudo gem install weechat terminal-notifier
    $ curl https://raw.github.com/wallace/weechat-notification-center-rb/master/notification_center.rb > ~/.weechat/ruby/autoload/notification_center.rb
    $ sudo weechat # for Yosemite

