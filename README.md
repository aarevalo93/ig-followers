# ig-followers

bot = Test('xxxxxx','xxxxxx',
                like_per_day=1000,
                media_max_like=0,
                media_min_like=0,
                follow_per_day=10,
                follow_time=24=60=60,
                unfollow_per_day=5,
                comments_per_day=0,
                tag_list=('fashion', 'style', 'outfitoftheday', 'swag', 'dress', 'styles'),
                max_like_for_one_tag = 5,
                unfollow_break_min = 15,
                unfollow_break_max = 30,
                log_mod = 0)
bot.auto_mod()
