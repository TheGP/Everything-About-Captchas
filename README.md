# Captcha Solving list of tools

# Detection & Scoring
* [Cloudflare turnstile](https://nowsecure.nl) - check if you are passing the Cloudflare captcha 
* [AntCPT reCaptha 3 score](https://antcpt.com/score_detector/) - see you reCaptha v3 score
* [Appspot reCaptha 3 score](https://recaptcha-demo.appspot.com/recaptcha-v3-request-scores.php) - another scoring tool for reCaptha v3
* [reCaptcha 2 demo](https://www.google.com/recaptcha/api2/demo) - demo of reCaptcha v2

For improving your score you should use [better fingerprint](https://github.com/TheGP/untidetect-tools) or [proxies](https://github.com/TheGP/4g-proxies-providers).

# Captha solvers
As each service differs with different captchas support, I took the most popular one: reCaptcha v2 1000 captchas to compare the price:
* [Capsolver](https://dashboard.capsolver.com/passport/register?inviteCode=U2gREjbK6qnY) - AI. $0.8. Supports Outlook & Arksose captchas.
* [2captcha](https://2captcha.com/?from=21664443) - human. Libs: JS, GO, PHP, Python, Ruby, C#, Java. $1-2.99 (doesn't work for Outlook)
* [CaptchaAI](https://captchaai.com/?from=175374) - AI, fixed price from $13.5/month for 5 captcha treads.
* [CapMonster](https://capmonster.cloud/) - AI. $0.6
* [SolveCaptcha](https://solvecaptcha.com?from=434017) - human. Many ready-to-use libs. $1
* [CapGuru](https://cap.guru/en/regen/?ref=144789) - unsure. Same API as Rucaptcha. $0.55
* [NopeCha](https://nopecha.com/) - AI. Starts from $5/month for 2k captchas/day.
* [MetaBypass](https://metabypass.tech/) - AI. Libs: Go, PHP, Python. $3
* [EzCaptcha](https://dashboard.ez-captcha.com/#/register?inviteCode=oewYJRREtMU) - AI.	$0.6
* [AntiCaptcha](http://getcaptchasolution.com/gy01xuqodw) - $0.95, AI
* [HardCaptcha](https://hardcaptcha.com/signup?rc=WOHWELMAWC) - start from $79/month, AI.

The easiest way to integrate these services is to use their extensions and watch for their callback on solving.

# Captcha services
If you like to add a captcha to your project

## Services
* [Google reCaptcha](https://www.google.com/recaptcha/about/) - 10k/month free ([Setup](https://docs.themeum.com/tutor-lms/tutorials/create-recaptcha-keys/), [React](https://www.npmjs.com/package/react-google-recaptcha), [Laravel](https://github.com/josiasmontag/laravel-recaptchav3/), [Another Laravel](https://github.com/anhskohbo/no-captcha))
* [hCaptcha](https://www.hcaptcha.com/) - 1m/month free ([Setup](https://melapress.com/support/kb/captcha-4wp-get-hcaptcha-keys/), [React](https://www.npmjs.com/package/@hcaptcha/react-hcaptcha), [Vue](https://github.com/hCaptcha/vue-hcaptcha))
* [Cloudflare Turnstile](https://www.cloudflare.com/products/turnstile/) - 10 widgets free with unlimited traffic ([React](https://www.npmjs.com/package/react-turnstile), [Vue3](https://www.npmjs.com/package/cfturnstile-vue3), [Others](https://developers.cloudflare.com/turnstile/community-resources/))
* [Altcha](https://altcha.org/) - open-source & GDPR compliant, can be self-hosted, if use their API 200 requests/day free ([Laravel](https://github.com/grantholle/laravel-altcha), [Others](https://altcha.org/docs/integrations/))
* [FriendlyCaptcha](https://friendlycaptcha.com/) - 1k/moth free for non-commercial websites ([React](https://github.com/FriendlyCaptcha/friendly-captcha-react), [Laravel](https://github.com/FriendlyCaptcha/friendly-captcha-laravel), [Others](https://friendlycaptcha.com/integrations/))
* [Captcha.eu](https://www.captcha.eu/) - GDPR-compliant paid captcha
* [Arkose](https://www.arkoselabs.com/arkose-matchkey/) - only paid, enterprise

## Libraries
* [Svg-captcha](https://github.com/produck/svg-captcha) - SVG captcha for Node.js
* [Captcha for Laravel](https://github.com/mewebstudio/captcha) - simple captcha for Laravel 5-11+
* [Gregwar/Captcha](https://github.com/Gregwar/Captcha) - simple PHP captcha library
* 
