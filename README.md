<p align="center"><img src="images/hero.png" width="100%" alt="Albrhi for WhatsApp"></p>

<h1 align="center">Albrhi for WhatsApp</h1>

<p align="center">
  <b>Privacy for WhatsApp, in your hands.</b><br>
  <span dir="rtl">خصوصيتك بيدك</span>
</p>

<p align="center">
  <img alt="version" src="https://img.shields.io/badge/version-0.3.0-2AD078?style=flat-square">
  <img alt="WhatsApp" src="https://img.shields.io/badge/WhatsApp-26.44.72-0B6E3D?style=flat-square">
  <img alt="jailbreak" src="https://img.shields.io/badge/jailbreak-roothide%20%C2%B7%20rootless-14A38B?style=flat-square">
  <img alt="price" src="https://img.shields.io/badge/price-free-2AD078?style=flat-square">
  <img alt="source" src="https://img.shields.io/badge/source-closed-555?style=flat-square">
</p>

Albrhi only ever **withholds**. It holds back what would leave your phone, or refuses a delete order that arrives. It never sends anything untrue.
Every switch is **off until you turn it on**, and says in one line what it costs.

---

## Install

1. **Let WhatsApp be tweaked.** On a jailbreak with per-app injection (roothide's tweak manager, Choicy and similar), allow tweaks in WhatsApp.
2. **Add the source** in Sileo or Zebra:
   ```
   https://ibrahim2100.github.io/albrhi-repo/
   ```
3. **Install _Albrhi for WhatsApp_.** Pick the package named **`.roothide`** on a roothide jailbreak, the other one on rootless.
   Prefer a file? Both `.deb`s are on the [Releases](../../releases/latest) page.
4. **Open WhatsApp.** The settings are a card at the top of WhatsApp's own **You** tab, and a button beside the “…” at the top of the chat list.

> [!NOTE]
> Built and tested against **WhatsApp 26.44.72**. On another version, a feature whose WhatsApp method has moved switches itself off on its own and the rest keeps working; *Settings › Tools › WhatsApp compatibility* says which.

## What it does

| | Feature | What happens | Status |
|---|---|---|---|
| 👁 | **No blue ticks** | the read receipt is not sent; you still see theirs | beta |
| 💬 | **No typing / recording** | “typing…” and “recording…” are not sent | beta |
| 🎙 | **No “played” on voice notes** | the sender's microphone stays grey | beta |
| ◌ | **No “seen” on statuses** | your name is not listed among who watched | beta |
| 🗑 | **Keep deleted messages** | a message deleted for everyone stays, with a small red bin; tap it for the whole story | **verified** |
| ✏️ | **Edited messages** | a pencil opens every version, before and after | beta |
| ⏳ | **Disappearing messages that stay** | timed messages stay, marked with an hourglass | not yet seen on a message that really expired |
| 👀 | **View once, again** | view-once photos and videos open like ordinary media; the sender is told only when you press the eye | beta |
| ◍ | **Statuses** | deleted statuses stay; the viewer gets an eye (mark seen when you choose) and an arrow (save to Photos) | save: **verified** · eye: beta |
| 👥 | **Per person, per group** | each privacy switch can apply to everyone, to chosen chats, or to everyone except them; a card on a contact's info page does it for that person | beta |
| ↪️ | **Forwarding** | hide the “Forwarded” label, and an **∞** button that lifts the five-chat limit | beta |
| 🌙 | **Appear offline** | the “online” announcement is not sent | experimental |
| ⚙️ | **Profiles** | *Ghost*, *Quiet* and *Keeper* set the switches in one go | works |
| 🔎 | **Search** | find any switch by its words, in Arabic or English | works |

**Verified** means watched working end to end. **Beta** means hooked on the right path and counted, but not yet watched from the other side; the settings page shows a BETA tag until a feature has been.
It has been verified in the iOS Simulator (iOS 17 and iOS 26) with a real account; results from iPhones are still being collected, which is why most features are marked beta.

## A look

<p align="center">
  <img src="images/card-1-privacy.png" width="19%" alt="The main page">
  <img src="images/card-2-profiles.png" width="19%" alt="Profiles">
  <img src="images/card-3-receipts.png" width="19%" alt="Receipts">
  <img src="images/card-4-deleted.png" width="19%" alt="Deleted and edited">
  <img src="images/card-5-status.png" width="19%" alt="Statuses">
</p>

<sub>The screens are the tweak's own pages, captured from the iOS Simulator. No chat, contact or message is shown.</sub>

## Good to know

- **It sends nothing of its own.** Albrhi makes no network requests; the only link it opens is one you tap on its About page. What it remembers (kept messages, edit history) stays on your phone.
- **Free, closed source.** It is free to use under the terms in [LICENSE](LICENSE). The source code is not published.
- **Risk.** WhatsApp's terms do not allow modified clients, and an account can be restricted for using one. Albrhi never sends anything untrue, but you use it at your own risk. Heavy forwarding (the **∞** button) is the riskiest thing in it, and its switch says so.
- **Two switches deliberately do something you can undo:** pressing the eye in the status viewer or on a view-once message tells the other side you looked. That is the point of the button.

## Report a problem

Open an [issue](../../issues/new/choose). Please include the report: *Albrhi › Tools › Copy the report* (it lists which features ran and which WhatsApp methods were found; look it over before you post it).
Please do **not** post chats, names or phone numbers.

## بالعربي

**البرهي للواتساب** أداة لجوالات الجيلبريك تمنع فقط: تمسك اللي كان بيطلع من جوالك (الصحّين الزرق، «يكتب…»، «تم التشغيل» للرسائل الصوتية، «شوهدت» للحالات)، وترفض أمر حذف يوصل جوالك فتبقى الرسالة المحذوفة مع سلّة حمراء صغيرة. ما ترسل شي غير صحيح أبداً، وكل مفتاح مطفي لين تشغّله ويقول لك سطر واحد وش ثمنه.

**التثبيت:** أضف المصدر `https://ibrahim2100.github.io/albrhi-repo/` في Sileo أو Zebra، ثم ثبّت «Albrhi for WhatsApp» (حزمة `.roothide` للـroothide، والثانية للـrootless). الإعدادات في بطاقة أعلى تبويب «أنت» داخل واتساب. الواجهة بالعربي أو الإنجليزي من الإعدادات › اللغة.

مجانية، وكودها مغلق. الحالة صادقة: الميزة اللي ما انشافت تشتغل من الطرف الثاني عليها علامة BETA.

## License

Free to use for your own personal, non-commercial use, as distributed; all rights reserved by the author. See [LICENSE](LICENSE). Not affiliated with, endorsed by or connected to WhatsApp LLC or Meta; “WhatsApp” is a trademark of its owner.

<p align="center"><sub>Made by Ibrahim Ismail AL-Rahn · <a href="https://instagram.com/Ib.11p">Instagram @Ib.11p</a> · <a href="https://t.me/Ib11p">Telegram @Ib11p</a></sub></p>
