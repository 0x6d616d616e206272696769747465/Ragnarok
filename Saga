import sys
reload(sys)
sys.setdefaultencoding('utf8')
import twitter

consumerAPI = '';
consumerSecret = '';
accessToken = '';
accessSecret = '';

api = twitter.Api(consumer_key=consumerAPI, consumer_secret=consumerSecret, access_token_key=accessToken, access_token_secret=accessSecret);
timeline = api.GetUserTimeline(screen_name='');

file = open("tweets.txt", "a",);

for tweet in timeline:
  file.write(tweet.text);
  file.write("\n");
file.close()

#for tweet in timeline:
#    print tweet.text;
