usage: redditwp [-h] [--min-score MIN_SCORE] [--debuglevel DEBUGLEVEL]
                [--directory DIRECTORY] [--list {hot,top,new,random,rising}]
                [--time {hour,day,week,month,year,all}] [--hq HQ]
                [--count COUNT] [-subfolders] [-nsfw] [-ignore-cache]
                subreddits [subreddits ...]

Get wallpapers from your choice of subreddits!

positional arguments:
  subreddits            Your choice of subreddits where to download Images

optional arguments:
  -h, --help            show this help message and exit
  --min-score MIN_SCORE
                        Minimum score to download (default: 500)
  --debuglevel DEBUGLEVEL
                        Set debug level (default: 20)
  --directory DIRECTORY
                        Download directory (default:
                        /home/uscpe/images/wallpapers)
  --list {hot,top,new,random,rising}
                        Subreddit list (default: hot)
  --time {hour,day,week,month,year,all}
                        Subreddit time (dont work with new or hot) (default:
                        all)
  --hq HQ               If you want to download only high quality photos
                        (default: 1920x1080)
  --count COUNT         Number of threads to check (default: 25)
  -subfolders           Store in subfolders with subredditname (default:
                        False)
  -nsfw                 Download nsfw (default: False)
  -ignore-cache         Ignore previously cached urls (default: False)

