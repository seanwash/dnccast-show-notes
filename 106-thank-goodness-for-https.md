# Thank Goodness for HTTPS

In episode 106 of Does Not Compute, Sean and Paul talk about the importance of HTTPS and VPNs, 1Password and RememBear, and using PostGIS to build location aware features for into your app.

---

Thanks to StoryBlocks for sponsoring this week's episode! [https://storyblocks.com/doesnotcompute](Storyblocks) is your one stop shop for high quality stock media at a fraction of the cost. Download all the stock your heart desires from their Member Library, including 400K images, 150K videos, and 100K audio clips. All content is royalty-free so you can use it for commercial and personal projects. New content is added regularly so there’s always something fresh to download!

Normally you could get a single part of the library (video, audio or photo) for $149 but if you visit [https://storyblocks.com/doesnotcompute](https://storyblocks.com/doesnotcompute) you'll get all three for $149. Offer ends December 31st 2017

## Things Mentioned

* [UnlimitedVille](https://unlimitedville.com/)
* [Nord VPN](https://nordvpn.com/)
* [TunnelBear](https://www.tunnelbear.com/)
* [Encrypt.me](https://encrypt.me/)
* [RememBear](https://www.remembear.com/)
* [1Password](https://1password.com/)
* [Al Franken - Facebook Russia investigation](http://fortune.com/2017/10/31/franken-facebook-russia-investigation/)
* [Comcast continues to inject its own code into websites you visit](https://thenextweb.com/insights/2017/12/11/comcast-continues-to-inject-its-own-code-into-websites-you-visit/)
* [HTTPS Everywhere](https://www.eff.org/https-everywhere)
* [Electronic Frontier Foundation](https://www.eff.org/)
* [Key Reinstallation Attacks – Breaking WPA2 by forcing nonce reuse](https://www.krackattacks.com/)
* [Telegram](https://telegram.org/)
* [WhatsApp](https://www.whatsapp.com/k)
* [SpiderOak - One](https://spideroak.com/one/)
* [PostGIS](http://postgis.net/)
* [PostGIS - ST_Distance()](https://postgis.net/docs/ST_Distance.html)
* [Elixir - Geo](https://github.com/bryanjos/geo)
* [Ecto - fragment/2](https://hexdocs.pm/ecto/Ecto.Query.API.html#fragment/1)
* []()
* []()

### ST_Distance with Elixir/Ecto

```elixir
... ecto query
|> select([s], fragment("ST_Distance(ST_GeogFromText(?), ST_GeogFromText(?))", ^point_a, ^point_b))
```

## Leave us a review

Last but not least, if you haven't rated or reviewed the show yet and you'd like to do us a huge favor, [you can do so by clicking here!](https://itunes.apple.com/us/podcast/does-not-compute/id1048731980?mt=2)

## Show Notes Archive

If you're looking for a link we've mentioned in the past, head on over to the [Does Not Compute Show Notes](https://github.com/seanwash/dnccast-show-notes) repo and use GitHub's excellent search tool!

## Join Us On Slack

If you've enjoyed the show so far, reach out to us on twitter at @seanwashbot and @paulstraw, or join us in the Spec.fm slack community at [http://spec.fm/slack](http://spec.fm/slack)!
