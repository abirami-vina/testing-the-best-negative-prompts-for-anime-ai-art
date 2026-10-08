# Testing the Best Negative Prompts for Anime AI Art on Tsubaki.3

> Looking for the best negative prompts for anime AI art? We tested Tsubaki.3 on unwanted text, busy backgrounds, and extra characters to see what helps.

<img width="1677" height="938" alt="An anime alchemist with mint-green hair holds up a glowing potion as golden runes drift into sparkles, next to the title Best Negative Prompts for Anime AI Art." src="https://github.com/user-attachments/assets/6424d4bf-a6ed-4b25-ad75-9ee43d73065c" />

*The right prompt wording can keep unwanted details out of your anime AI art without a long negative list.*

Suppose you're using an AI image generator to create a character standing outside a small potion shop. Let's say you finally get the image you wanted. Your character looks perfect, and the little shop behind him is exactly what you pictured. Then you notice the sign above the door. It reads "Samice Piay."

So you try the fix most guides suggest. You add "Text, letters, writing" to the negative prompt, the box where you list things you don't want the model to draw, and generate again. The letters change shape, but the sign still says something odd.

That happened in our own tests, and it made us question how useful lists of the best negative prompts for anime AI art really are. Many anime negative prompts get copied from one model to the next without much testing, and sometimes the better fix isn't another exclusion at all.

So we put negative prompts for anime AI art to the test using [Tsubaki.3](https://eap.pixai.art/go/abirami2), the newest anime model from [PixAI](https://eap.pixai.art/go/abirami). While using Tsubaki.3, you'll find a separate Negative field under Advanced in the settings, already filled with a short default list. We kept that default and compared three fixes. We added exclusions to the field, rewrote the main prompt to describe what we wanted, and edited the finished image.

Our test subject is Elio, an original alchemist who sells glowing potions from a lantern-lit cart in a floating night market. He has mint-green hair that fades to lavender, gold eyes, a plum coat with brass clasps, and a tiny orange salamander on his shoulder.

<img width="1216" height="1632" alt="Anime alchemist with mint-green hair and an orange salamander on his shoulder, standing beside a potion cart at night." src="https://github.com/user-attachments/assets/bef47c76-cbbf-47ba-beaa-ec67e882d4eb" />

*Elio, the original alchemist used in every test in this article, was generated and refined with Tsubaki.3 in PixAI.*

His world is full of shop signs, crowded workbenches, and busy streets. That gave us plenty of chances to test unwanted text, clutter, and extra characters.

The short version is that describing what we wanted worked better than adding negative terms. When something still went wrong, a quick edit fixed what the prompts missed.

Tsubaki.3 reads full scene descriptions the way an illustrator reads a brief, so small wording changes can change the whole picture. If you're wondering how to improve anime AI art without guessing, learning about [Tsubaki.3 prompts](https://blog.pixai.art/en/tsubaki-3-prompt-guide/) can actually make a difference.

In this article, we'll put anime negative prompts to the test in three scenes. We'll try to keep text off a shop sign, clear the clutter from a busy workshop, and keep Elio alone on a snowy train platform, then finish with one targeted edit. Let's get started!

## How Negative Prompts for Anime AI Art Work in Tsubaki.3

The term "negative prompt" can mean different things depending on the tool you use. So, before we test anything, let's first look at where these instructions go.

There are three ways to tell Tsubaki.3 what you don't want in an image. You can add terms to the Negative field, mention what to avoid in the main prompt, or describe what you want to see instead.

Only the first one is technically a negative prompt. They all share the same goal of keeping unwanted details out, but they give a model that instruction in different ways.

On Tsubaki.3, you can use all three. Here's the Generate tab we used for our tests, with the main prompt on the left and the Negative field under Advanced on the right.

<img width="1854" height="1037" alt="PixAI Generate tab showing the prompt box, the Prompt Helper setting, and the Negative and Seed fields." src="https://github.com/user-attachments/assets/cd257afc-439e-487e-9205-2a887e0a76ed" />

*The Tsubaki.3 Generate tab shows the main prompt, the Prompt Helper setting, and the pre-filled Negative field and Seed box under Advanced.*

Here's a closer look at the three ways to steer a Tsubaki.3 image away from something you don't want:

- **Negative Field:** This is a separate box under Advanced in the settings panel. It takes short, comma-separated terms and comes pre-filled with "Lowres, worst quality, low quality, bad anatomy, explicit."
- **Exclusion in the Main Prompt:** You can also add a sentence to the main description that tells the model what to leave out, like "Do not include any clutter or other objects in the background."
- **Positive Description:** Rather than saying what to avoid, you can describe what you want to see, like "He stands against a plain, softly lit dark blue backdrop."

Here's an example to make this clearer. Consider trying to get a clean background behind Elio. Each approach asks for the same thing, but each one words the request differently.

<img width="940" height="545" alt="Diagram showing three ways to write the same background request below a banner of an anime alchemist." src="https://github.com/user-attachments/assets/a779454a-5ac1-4b92-b899-6e1b38c28d63" />

*A simple background for Elio can be requested through the Negative field, as an exclusion in the main prompt, or as a positive description.*

The last two approaches are especially close. One tells Tsubaki.3 what to remove, while the other describes what should be there. That small difference is what we wanted to test. Our tests compare the Negative field with positive wording, and you'll see the background results in Test 2.

Other anime models may handle these inputs differently, so the best negative prompts for anime AI art on one model won't always carry over. Since PixAI includes a dedicated Negative field when you use Tsubaki.3, we put our exclusions there and compared them with positive descriptions written in the main prompt.

## Testing the Best Negative Prompts for Anime AI Art on Tsubaki.3

We built three tests around problems anime creators often try to fix with negative prompting. The first looked at unwanted text in a scene with plenty of places for it to appear. The second focused on getting a simple background behind Elio, while the third checked whether extra characters would appear in a busy scene.

Within each test, we compared three versions of the same prompt, using two of the three approaches from the previous section. Version A described the scene without mentioning the problem, giving us a baseline. Version B kept that description and added a few terms to the Negative field, while Version C rewrote the description to spell out the desired result. We focused on the Negative field and positive wording because they're the two approaches that differ the most.

<img width="2048" height="1241" alt="Diagram of three prompt versions next to an anime alchemist at his potion cart." src="https://github.com/user-attachments/assets/dcfb5f12-75b1-4987-8313-dda02ca4bab6" />

*Each test kept the same character and settings, and changed either the Negative field in Version B or the main prompt in Version C.*

To keep the comparison fair, and so you can repeat it yourself, every image used the same setup. That meant Tsubaki.3 (v1) in Pro mode, a 3:4 portrait shape, and XL size (1232 × 1632), with one image at a time. We skipped anything that could change the look on its own, like [LoRAs](https://blog.pixai.art/en/what-is-lora-beginners-guide/) (small add-ons that teach a model a style or character), reference images, style presets, and the Quality Tag booster. We also kept the default Negative list in every version.

On top of this, we fixed the seed. A seed is a number that sets an image's random starting point, a bit like shuffling a deck of cards the same way each time. Running the same prompt twice at seed 1111 gave us identical images, so we ran every version at seeds 1111 and 2220. That way, any difference comes from the wording or Negative field terms we changed. Even with the same seed, though, a small wording change can shift the whole image, not just the part you meant to fix.

The last thing we had to check before running the tests was Prompt Helper. It's a setting that's on by default, rewrites your prompt before it reaches the model, and it turned our sentences into tags. Since we were testing exact wording, we needed Tsubaki.3 to see our prompts as typed.

Even with the helper off, the word "alchemist" still pulled in a character tag from an existing game. Describing Elio as a potion maker fixed that, and each image's details panel confirmed our Tsubaki.3 prompts reached the model exactly as typed.

<img width="1700" height="1450" alt="Three anime alchemist images, each shown next to the prompt PixAI sent to the model." src="https://github.com/user-attachments/assets/82a0e732-80d8-4cb8-8388-ad68661cd4f8" />

*Prompt Helper rewrote the prompt into tags.*

Keep in mind, our tests were a small, hands-on experiment with six images per task, not a full benchmark, so a different character or scene could turn out differently. Now that everything is set up, let's start with the first test and see whether we can keep text out of the scene.

## Test 1: Can Negative Prompts Keep Text Out of Anime Art?

"Text" is one of the most common terms in anime negative prompts, and for good reason. Anime models can fill signs, posters, and labels with lettering even when the prompt never asks for it.

To test that, we put Elio in the doorway of his potion shop on a sunny morning, surrounded by a signboard, a chalkboard, and a window full of bottles. We didn't ask for any writing.

Here's the prompt we used for Version A.

```text
A charming potion maker in his early twenties stands in the open doorway of his small potion shop on a narrow cobblestone street in the morning. He has shoulder-length messy mint-green hair that fades to lavender at the tips, bright gold eyes and a relaxed, confident smile as he holds up a small glowing vial. He wears a long buttoned plum coat that reaches his shins, fastened with ornate brass clasps over a plain white shirt with an open collar, a leather belt lined with glowing potion vials, round amber goggles pushed up on his head and dark boots with brass toe caps. A tiny orange salamander with a spiky back rides on his shoulder. A large wooden signboard hangs above the shop door, a chalkboard easel stands beside the entrance, and the shop window is lined with rows of glass potion bottles. Hanging plants and a brass lantern frame the doorway. Three-quarter shot from a slightly low angle. Soft golden morning light with long shadows. Anime-style character with clean linework against a semi-realistic painted background with atmospheric haze, highly detailed.
```

For Version B, we kept that exact prompt and added three tag-style terms to the Negative field, since short tags suit that box.

```text
Lowres, worst quality, low quality, bad anatomy, explicit, text, letters, writing
```

For Version C, we left the Negative field on its default and rewrote one sentence of the main prompt to describe each surface as blank.

```text
A plain, unpainted wooden signboard hangs above the shop door, a clean blank chalkboard easel stands beside the entrance, and the shop window is lined with rows of unlabeled glass potion bottles.
```

The difference showed up immediately.

<img width="1900" height="1150" alt="Three anime shop-front images with magnified views of each signboard." src="https://github.com/user-attachments/assets/7e62ed45-5cb8-4d04-bd6c-32cdfd8ea1b5" />

*At seed 1111, the baseline and Negative field versions both put letter-like marks on the sign, while the positive description left it blank.*

Version A carved a made-up shop name into the signboard and filled the chalkboard with rows of handwriting, all on its own. Adding "Text, letters, writing" in Version B changed the shapes of those letters, but the sign still said something. Only Version C returned a blank sign and a clean chalkboard.

The pattern held across both seeds. Version A put lettering on the signboard and chalkboard every time, and at seed 2220, it also added text to a hanging sign and a wall plaque. Version B changed the letter shapes and removed one small hanging sign at seed 2220, but the signboard and chalkboard still had text in both images. Version C was the only one that stayed blank at both seeds, with no letter-like marks anywhere.

<img width="1840" height="1170" alt="Film strip of three anime shop-front images generated at seed 2220." src="https://github.com/user-attachments/assets/988221c4-7266-47a5-b119-ef6dfda2e9ca" />

*At seed 2220, the Negative field removed one small hanging sign, and only the positive description cleared every surface.*

So the positive description won on text. It came at a cost, though. Rewriting that one sentence changed the sign style, the easel, and the shop layout in Version C, and at seed 1111 the word "unlabeled" added blank paper labels to bottles that had none before. Mentioning something, even to rule it out, can pull it into the picture.

<img width="1610" height="1050" alt="Grid of six chalkboard close-ups next to a crop of potion bottles with blank labels." src="https://github.com/user-attachments/assets/ad1cf39c-93ae-445f-bc37-4d00820c2e0c" />

*The chalkboards carried text in every baseline and Negative field image, and at seed 1111 the word "unlabeled" added blank labels to the bottles.*

Neither approach left the scene untouched. The Negative field kept the shop and the lettering, while the positive description cleared the lettering but redrew parts of the shop. If a blank sign is the goal, though, describing it worked far more reliably than telling Tsubaki.3 what to avoid.

## Test 2: Do Negative Prompts Simplify Busy Anime Backgrounds?

For the next test, we wanted to see whether negative prompts could make a busy setting easier to control. We were aiming for a portrait that could work on a profile card, where Elio stands out, and nothing behind him competes for attention. So we moved him into his potion workshop, a place naturally crowded with jars, books, and glassware, and sat him on a tall stool studying a glowing flask.

Here's the prompt we used for Version A. It names the workshop but says nothing about how the background should look.

```text
A charming potion maker in his early twenties sits on a tall wooden stool in his potion workshop, one boot resting on the rung, holding a round glass flask up to eye level as glowing green smoke swirls inside it. He studies the flask with a curious, confident smile while its green glow lights up his face. He has shoulder-length messy mint-green hair that fades to lavender at the tips and bright gold eyes. He wears a long, buttoned plum coat that reaches his shins, fastened with ornate brass clasps over a plain white shirt with an open collar, a leather belt lined with glowing potion vials, round amber goggles pushed up on his head and dark boots with brass toe caps. A tiny orange salamander with a spiky back rides on his shoulder, leaning in to peer at the flask. Medium full shot from eye level. Warm candlelight from the left mixed with the green glow of the flask. Anime-style character with clean linework and semi-realistic painted shading, highly detailed.
```

For Version B, we kept the same prompt and added three terms to the Negative field.

```text
Lowres, worst quality, low quality, bad anatomy, explicit, cluttered background, crowd, extra objects
```

For Version C, we left the Negative field on its default and added one sentence to the prompt, right after the salamander.

```text
The workshop behind him fades into a plain, softly lit dark blue backdrop.
```

Here's what the three versions looked like at seed 1111.

<img width="2048" height="899" alt="Three anime images of an alchemist on a stool, with the background getting simpler from left to right." src="https://github.com/user-attachments/assets/c57079d4-d1d5-48dc-a80e-eab05f75868a" />

*Three versions at seed 1111 show a full workshop, a trimmed workshop, and a plain blue backdrop from left to right.*

The three results took different approaches to the same workshop. Version A filled the background with shelves, books, a quill, candles, and a cabinet, with much of it sitting right beside Elio's elbow. Version B cleared out the shelf, books, quill, and cabinet, giving him a little more room without removing the workshop altogether. Version C went further and replaced the room with the blue backdrop we described, making Elio stand out much more clearly.

The second seed made the difference even clearer.

<img width="2048" height="899" alt="Three anime images of an alchemist on a stool generated at a second seed." src="https://github.com/user-attachments/assets/44dc2bbb-4190-4c54-935c-cee28e666f45" />

*At seed 2220, the middle version moved things around instead of simplifying the workshop, while the version on the right produced the plain blue backdrop again.*

At seed 2220, Version B changed the background rather than simplifying it. One flask disappeared, but a fuller shelf and an arched window appeared on the other side of the room. Version C produced the plain backdrop again, and across all six images, none of Elio's details went missing.

If we judge the results by the profile card goal rather than by which image looks nicest, Version C came closest. It wasn't a perfect cutout, though. Because the prompt still mentioned a workshop and a stool, every Version C image kept a desk with candles and flasks behind him, so you'd still need some cropping for a completely clean background.

We also got one other unexpected result. In an early run, we left the setting out of the prompt completely, and Tsubaki.3 chose a plain backdrop on its own. That suggests the setting you describe can add clutter just as easily as a negative term can remove it.

So for this test, describing the background we wanted gave us much more control than listing the things we wanted Tsubaki.3 to leave out.

## Test 3: Will Anime Negative Prompts Keep Extra Characters Out?

The first two tests focused on things in the scene, like signs and clutter. Extra people are a little different. Put a character somewhere busy, and a model can fill the background with passersby you never asked for. That's one reason creators often reach for anime negative prompts.

So for our third test, we put Elio somewhere that's usually full of people, a snowy train station on a winter morning. He sits on his travel trunk with a warm mug while an old steam train waits beside him.

Here's the prompt we used for Version A.

```text
A charming potion maker in his early twenties sits on a large leather travel trunk on a snowy train station platform in the morning, warming his hands around a steaming mug as snowflakes drift down. He looks toward the viewer with a calm, happy smile. He has shoulder-length messy mint-green hair that fades to lavender at the tips and bright gold eyes. He wears a long buttoned plum coat that reaches his shins, fastened with ornate brass clasps over a plain white shirt with an open collar, a leather belt lined with glowing potion vials, round amber goggles pushed up on his head and dark boots with brass toe caps. A tiny orange salamander with a spiky back is curled up on his shoulder, glowing faintly to keep warm. An old steam train waits at the platform, releasing clouds of white steam, and iron lamp posts line the snowy platform. Medium full shot from eye level. Soft cool morning light with falling snow. Anime-style character with clean linework against a semi-realistic painted background with atmospheric haze, highly detailed.
```

For Version B, we kept the same prompt and added three terms to the Negative field.

```text
Lowres, worst quality, low quality, bad anatomy, explicit, crowd, multiple people, extra characters
```

For Version C, we left the Negative field on its default and added one sentence after the lamp posts.

```text
He is the only person at the station, and the long snowy platform around him is empty.
```

And here's what we got at seed 1111.

<img width="1792" height="888" alt="Three anime images of an alchemist sitting on a trunk at a snowy train station." src="https://github.com/user-attachments/assets/4a447a7d-8d82-41c7-b043-be68115fa6e2" />

*All three versions show Elio alone on the platform, while Version C redraws the station with a long roof and a head-on engine.*

The surprise was that Version A didn't need fixing. Tsubaki.3 left Elio alone on the platform at both seeds, with no passengers anywhere. So neither approach had anything to remove, but both still changed parts of the scene.

Here's what happened with each version:

- **Baseline:** Elio sat alone at both seeds, with the train, lamp posts, and his trunk all in place.
- **Negative Field:** No people appeared, but small details shifted, like a new iron pillar at seed 1111 and a roof edge at seed 2220.
- **Positive Description:** The station was redrawn at both seeds, with a long covered roof, rows of columns, and the engine turned to face the viewer.

The results at seed 2220 looked almost the same, so we've shown just one set here. None of Elio's details went missing in any version. We did notice one unrelated detail, though. Most of the engines picked up a number plate with made-up lettering, even though this test had nothing to do with text.

That gives us a useful takeaway. When a model already gets something right, extra instructions won't improve it. They end up changing parts of the scene you were already happy with.

Up to this point, we only changed the wording before generating each image. For our last test, we tried a different approach and edited an image that Tsubaki.3 had already created.

## When Editing Works Better Than More Tsubaki.3 Prompts

Sometimes an image is almost right. The character, pose, and lighting all work, but one corner of the scene keeps pulling your attention and needs editing. At that point, rewriting the prompt can be a gamble. A new generation might fix the messy corner, but it could also change the parts you already liked.

A targeted edit is another way to improve anime AI art. Instead of generating the whole image again, you can focus on the one part that needs fixing and leave the rest alone.

To see how that works, we went back to Version A from Test 2 at seed 1111. Elio looked great, but the workbench behind him was crowded with candles, flasks, bottles, and a quill, all sitting close to his elbow. The Negative field had only partly cleared that clutter in Test 2, so this time we tried editing the image directly.

We attached the image in Tsubaki.3 (as a reference) and gave it one instruction.

```text
@image1 Clear the workbench behind him by removing the candles, flasks, bottles and the quill, leaving a bare wooden bench. Keep the character, his glowing flask, the salamander, the stool, the brick wall and the lighting exactly the same.
```

<img width="1430" height="1278" alt="Before-and-after images of an anime alchemist, with the workbench behind him cleared in the edited version." src="https://github.com/user-attachments/assets/0876b2ce-61c1-4f72-9b90-28b4ae203862" />

*The original image, the edited result, and the instruction used to make the edit in Tsubaki.3.*

The edit did what we asked. The candles, flasks, bottles, and quill disappeared, leaving a bare wooden bench without smudges or half-erased shapes. Elio's face, pose, and outfit stayed the same, along with his glowing flask, the salamander, the stool, and the brick wall. Even the shelf of bottles along the top, which we never mentioned, stayed untouched.

A couple of small changes stood out. The warm glow on the wall remained even after the candles disappeared, so the lighting no longer had an obvious source. The frame also came back slightly narrower than the original.

Another factor to keep in mind is that editing works a little differently than generating a fresh image. Once an image is attached, the Negative field and Prompt Helper toggle disappear, leaving the written instruction as the only control. PixAI also lightly reworded our instruction before sending it to the model, although the meaning stayed the same.

Overall, this edit was a separate step, so it doesn't prove that any of our earlier prompts worked. What it does show is that when most of an image is right, a short, specific edit can fix the problem without generating the whole image again.

## Which Prompt Approach Helped Most on Tsubaki.3?

After three tests of negative prompts for anime AI art and one edit, no single approach won every round. Each one helped with certain problems and did little for others.

<img width="2000" height="1670" alt="Four anime alchemist images, each labeled with a task and whether Negative field terms, positive wording, or editing fixed it. " src="https://github.com/user-attachments/assets/bc50885e-cb86-4470-b437-b45c7c760b89" />

*A side-by-side look at how each approach performed across the three tests and the edit.*

Here's a closer look at when each approach helped:

- **When Exclusions Helped:** The Negative field had the smallest effect. Adding terms like "Text, letters, writing" changed small details but rarely removed the problem completely, and its effect on background clutter varied from seed to seed.
- **When Describing the Result Won:** Asking for blank surfaces or a plain background worked more reliably, and Tsubaki.3 followed that description at both seeds. The trade-off was that it also redrew more of the scene around the change.
- **When Editing Made Sense:** Once an image was already close, a short instruction cleared the whole workbench while keeping Elio, his pose, and the rest of the scene in place.

The character test also showed why adding instructions isn't always useful. Tsubaki.3 already kept Elio alone on the platform at both seeds, so the extra wording didn't solve a problem. It simply changed parts of the scene that were already working.

Generally, it helps to keep prompting and editing apart. Prompt wording shapes the image while it's being generated, while an edit works on an image that already exists. So a successful edit doesn't tell us anything about how well the original wording worked.

## How to Improve Anime AI Art: A Quick Cheat Sheet

You don't need a long list of terms to get cleaner anime art. A few small habits helped the most in our tests.

<img width="1216" height="1632" alt="An anime alchemist stands beside a large chalkboard listing four prompting tips." src="https://github.com/user-attachments/assets/b51ada7a-6835-44d5-a4ce-d499aa12762e" />

*Elio's chalkboard lists the four habits that helped most in our tests.*

First, write what you want. To keep text off signs, describe those surfaces as blank in the main prompt. We used "A plain, unpainted wooden signboard hangs above the shop door," and the sign stayed blank at both seeds. The catch is that this changed more of the scene, and "unlabeled" added blank labels to the bottles.

Next, name the setting you want. For a simple background, we added "The workshop behind him fades into a plain, softly lit dark blue backdrop" to the main prompt. The backdrop came out clean every time, but props the prompt mentioned, like the desk, still showed up.

If an image is almost right, edit one spot. Pass it to Tsubaki.3 as a reference and describe a single change, like our "Clear the workbench behind him" instruction, which removed everything we listed.

Finally, check the prompt. Turn Prompt Helper off in the settings, then open the Rewritten Prompt in the image's details panel. That's how we caught a hidden character tag.

The best negative prompts for anime AI art still have a place, and terms like "Text, letters, writing" did change small details in our tests. For bigger fixes, pairing them with a clear description of what you want will usually get you further.

## So, Do You Need Negative Prompts for Anime AI Art?

With Tsubaki.3, you rarely need negative prompts, even if you use the best negative prompts for anime AI art. The terms we added to PixAI's Negative field only changed some lettering and clutter. When we described the result we wanted, Tsubaki.3 gave us blank signs and a plain backdrop at both seeds. It also kept Elio alone at the station without help from either approach, and a short edit fixed the one image that was almost right.

A few things were still inconsistent. Positive wording sometimes redrew more of the scene, and single words like "unlabeled" added details we never asked for. These results come from one character, two seeds, and one model, so other anime models may behave differently.

If you'd like to try this yourself, start small. Open Tsubaki.3 on [PixAI](https://eap.pixai.art/go/abirami), pick one thing you'd usually rule out, and describe what you'd like to see there instead.
