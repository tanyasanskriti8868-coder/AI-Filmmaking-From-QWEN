 --THE LAST FILE-- 
  
1-Minute Sci-Fi Thriller Script 
Maintaining Character Consistency Using Hugging Face and Reference Images 
One of the biggest challenges in AI-generated video creation is maintaining character consistency across multiple 
scenes. Text-to-video models often generate slight variations in facial features, hairstyles, clothing, and expressions, 
causing the same character to appear different in each scene. Since my project consisted of a one-minute movie 
divided into twelve individual scenes, ensuring visual consistency was an important objective. 
To overcome this challenge, I first generated high-quality reference images for each of the three main characters 
using an open-source model available on Hugging Face. Instead of relying solely on text prompts, I used Hugging Face 
models integrated with Google Collab, which allowed me to generate detailed character portraits with greater 
control over appearance. Google Collab provided the computational environment required to run the model 
efficiently without requiring a high-end local GPU. 
Three separate reference images were created—one each for Aira, Dev, and Maya. Each character was assigned a 
unique and detailed visual identity, including facial structure, hairstyle, clothing, age, skin tone, body type, and 
accessories. These visual attributes were fixed and remained unchanged throughout the project. The generated 
images served as the official character references for every subsequent scene. 
During prompt engineering, these reference images were supplied along with detailed textual descriptions whenever 
a new video scene was generated. Every prompt included the same character names, physical descriptions, outfits, 
and personality traits. By repeatedly providing identical reference images and consistent descriptive prompts, the AI 
model was encouraged to preserve the same appearance across all twelve scenes. This significantly reduced 
inconsistencies in facial features, hairstyles, clothing colours, and overall character identity. 
2 
 
In addition to visual consistency, I also maintained behavioural consistency by assigning each character a distinct 
personality. Aira was consistently portrayed as calm and confident, Dev as intelligent but slightly nervous, and Maya 
as mysterious and observant. These personality traits were included in every prompt to ensure that facial 
expressions, body language, and interactions remained consistent throughout the story.i 
Using Hugging Face together with Google Collab offered flexibility and reproducibility during the image-generation 
process. The reference-based workflow improved the overall quality of the generated videos and created a more 
coherent cinematic experience. Rather than generating each scene independently, every scene was linked through 
the same set of reference images and character descriptions, allowing the audience to easily recognize each 
character from beginning to end. 
This approach demonstrates the importance of combining prompt engineering with reference-based generation 
when creating AI-generated films. By integrating Hugging Face models, Google Collab, and carefully designed 
prompts, I was able to maintain strong character consistency throughout the project, resulting in a more 
professional, visually coherent, and engaging short film. 
 
Characters: 
AIRA – Calm, intelligent leader 
DEV – Nervous but brilliant 
MAYA – Mysterious and observant 
 
SCENE 1 (0:00–0:05) 
VIDEO GENERATION PROMPT 
Use the uploaded character reference images exactly. 
 
Character Identification: 
 
AIRA = Indian woman wearing a dusty pink tactical jacket with zipper pockets, shoulder-length wavy black hair, sharp 
dark eyes, calm and intelligent leader. 
 
MAYA = Indian woman wearing a beige oversized hoodie with dark drawstrings, long dark wavy hair, large expressive 
3 
 
eyes, observant and mysterious personality. 
 
DEV = Indian man wearing a black oversized hoodie and black t-shirt, messy black hair, black rectangular glasses, 
nervous but brilliant personality. 
 
Maintain exact facial features, hairstyle, clothing, age, body proportions, and identity from reference images. 
 
Environment: 
 
A secret underground digital archive facility. Large circular futuristic server chamber. Dark metallic walls. Massive 
circular machine structure behind the central monitor. Giant glowing monitor wall displaying system data. Blue and 
white holographic lights. Industrial sci-fi atmosphere. Same room must be reused throughout the entire movie. 
 
Scene Description: 
 
The camera slowly pushes forward through the dark archive room. 
 
AIRA stands confidently in the centre near the giant monitor. 
 
DEV stands slightly to her right, nervous and constantly looking at the screen. 
 
MAYA stands slightly behind them, quietly observing everything. 
 
The giant monitor suddenly flickers. 
 
A warning appears: 
 
"FILE DELETES IN 60 SECONDS" 
 
The screen glow reflects across their faces. 
 
AIRA immediately becomes serious. 
 
DEV looks shocked and confused. 
 
MAYA narrows her eyes and studies the warning carefully. 
 
4 
 
Camera: 
 
Slow cinematic forward dolly shot. 
 
Medium-wide framing. 
 
Subtle camera shake. 
 
Focus transitions from monitor to characters. 
 
Realistic depth of field. 
 
Lighting: 
 
Blue-white monitor light illuminating faces. 
 
Dark sci-fi shadows. 
 
High contrast cinematic lighting. 
 
Atmosphere: 
 
Suspense. 
 
Mystery. 
 
Tension increasing every second. 
 
No action scene. 
 
No running. 
 
No explosions. 
 
No fantasy elements. 
 
Dialogue Timing: 
5 
 
 
0.0s - Monitor flickers. 
 
1.5s - Warning text appears. 
 
2.5s - AIRA speaks. 
 
AIRA (calm, authoritative, medium volume, fast pace): 
"Who opened it?" 
 
3.5s - DEV responds immediately. 
 
DEV (nervous, slightly louder, very fast speech): 
"Not me." 
 
4.3s - MAYA speaks quietly. 
 
MAYA (soft voice, controlled, slightly slow pace): 
"Then why is it counting down?" 
 
Voice Direction: 
 
AIRA = calm leader, confident, controlled breathing. 
 
DEV = anxious, rapid speech, nervous energy. 
 
MAYA = quiet, intelligent, mysterious tone. 
 
Natural lip sync. 
 
Professional cinematic voice acting. 
 
Realistic facial expressions. 
 
Ultra-realistic sci-fi thriller film scene. 
 
5-second movie shot. 
6 
 
 
A giant monitor flickers to life. 
SCREEN: FILE DELETES IN 60 SECONDS 
AIRA: Who opened it? 
DEV: Not me. 
MAYA: Then why is it counting down? 
SCENE 2 (0:05–0:10) 
If Qwen is not generating speech, simplify Scene 1. Too much camera movement, too many instructions, and 3 
speakers in 5 seconds can cause the model to ignore dialogue. 
Use this cleaner version: 
Use the uploaded character reference images exactly. 
AIRA = Indian woman wearing a dusty pink tactical jacket, shoulder-length wavy black hair, calm intelligent leader. 
DEV = Indian man wearing a black hoodie and glasses, nervous genius. 
MAYA = Indian woman wearing a beige hoodie, long dark wavy hair, observant and mysterious. 
Maintain exact facial features, hairstyle, clothing, age, and identity from reference images. 
Environment: 
Secret underground digital archive facility. 
Large futuristic monitor. 
Dark metallic walls. 
Blue and white monitor lighting. 
Same room used throughout the entire movie. 
IMPORTANT: 
All dialogue must be spoken clearly. 
7 
 
Every character must have visible lip movement. 
One character speaks at a time. 
No overlapping voices. 
No narration. 
No subtitles. 
Scene: 
AIRA, DEV, and MAYA stand in front of a giant monitor. 
The monitor suddenly glitches. 
Large red warning text appears: 
FILE DELETES IN 60 SECONDS 
The blue screen light reflects across their faces. 
AIRA looks at the warning and immediately turns toward the others. 
Dialogue: 
AIRA: 
"Who opened it?" 
AIRA speaks first. 
Pause. 
DEV: 
"Not me." 
DEV speaks second. 
Pause. 
MAYA: 
"Then why is it counting down?" 
MAYA speaks last. 
Facial Expressions: 
8 
 
AIRA = serious and focused. 
DEV = nervous and confused. 
MAYA = calm but suspicious. 
Camera: 
Static medium shot. 
No camera movement. 
No scene transitions. 
Realistic cinematic lighting. 
Ultra-realistic sci-fi thriller. 
High-quality facial animation. 
Natural speech. 
Perfect lip sync. 
5-second movie scene. 
A static camera is much more likely to make Qwen generate audible dialogue than a moving cinematic shot. Once 
speech works reliably, you can add camera motion in later scenes. 
 
SCENE 3 (0:10–0:15) 
Use the uploaded character reference images exactly. 
Maintain exact facial features, hairstyle, clothing, age, body proportions, skin tone, and identity from the reference 
images. 
CHARACTER IDENTIFICATION: 
AIRA = Indian woman wearing a dusty pink tactical jacket with a visible name patch reading "AIRA" on the left chest 
pocket, shoulder-length wavy black hair, sharp dark eyes, calm intelligent leader. 
DEV = Indian man wearing a black oversized hoodie with a visible name patch reading "DEV" on the chest, black 
rectangular glasses, messy black hair, nervous genius. 
9 
 
MAYA = Indian woman wearing a beige oversized hoodie with a visible name patch reading "MAYA" on the chest, long 
dark wavy hair, observant and mysterious. 
The name patches must remain visible and readable throughout the scene. 
ENVIRONMENT: 
Use the exact same underground digital archive facility from previous scenes. 
Same giant futuristic monitor. 
Same room layout. 
Same dark metallic walls. 
Same blue-white monitor lighting. 
Same circular machine structure behind the monitor. 
Same atmosphere. 
VOICE GENERATION PRIORITY: 
Generate real audible speech. 
Every dialogue line must be spoken. 
No silent characters. 
No narration. 
No subtitles. 
No overlapping voices. 
Perfect lip synchronization. 
Dialogue volume must be HIGH and clearly audible. 
Speech must be louder than background sounds. 
AIRA Voice: 
Female, calm, intelligent, confident, medium pitch, clear pronunciation, medium-high volume. 
10 
 
DEV Voice: 
Male, nervous, anxious, fast speaking speed, slightly shaky voice, high volume. 
MAYA Voice: 
Female, mysterious, controlled, soft but clearly audible, medium volume. 
SCENE 3: 
The glowing folder labelled ARCHIVE-0 suddenly opens by itself. 
No one touches the keyboard. 
No one touches the monitor. 
The giant screen flickers several times. 
A hidden video file automatically launches. 
A thumbnail appears. 
The thumbnail shows three dark silhouettes standing together. 
The silhouettes resemble AIRA, DEV, and MAYA. 
The room becomes unnaturally quiet. 
Blue monitor light reflects strongly across their faces. 
DEV steps half a step forward. 
AIRA stares at the screen. 
MAYA slowly narrows her eyes. 
All three are visibly disturbed. 
DIALOGUE TIMING: 
1.5 seconds 
DEV looks directly at the screen. 
DEV (high volume, nervous): 
11 
 
"Did anyone open that?" 
Pause. 
3.0 seconds 
AIRA keeps watching the monitor. 
AIRA (firm, clear, medium-high volume): 
"No. It opened itself." 
Pause. 
4.2 seconds 
MAYA continues staring at the silhouettes. 
MAYA (controlled, mysterious, clearly audible): 
"That's not possible." 
FACIAL EXPRESSIONS: 
DEV = shocked, confused, nervous. 
AIRA = serious, focused, suspicious. 
MAYA = disturbed, observant, uneasy. 
CAMERA: 
Static medium shot. 
Monitor visible behind the characters. 
No camera movement. 
No scene transition. 
Focus on lip synchronization and spoken dialogue. 
LIGHTING: 
Strong blue monitor glow. 
12 
 
Dark sci-fi shadows. 
High tension atmosphere. 
Ultra-realistic cinematic sci-fi thriller. 
Professional acting. 
Natural speech. 
Perfect lip sync. 
5-second movie scene. 
 
ARCHIVE-0 opens automatically. 
A thumbnail appears showing three silhouettes. 
DEV: Did anyone open that? 
AIRA: No. It opened itself. 
MAYA: That's not possible. 
SCENE 4 (0:15–0:20) 
Use the uploaded character reference images exactly. 
Maintain exact facial features, hairstyle, clothing, age, body proportions, skin tone, and identity from previous 
scenes. 
CHARACTER IDENTIFICATION: 
AIRA = Indian woman wearing a dusty pink tactical jacket with a visible name patch reading "AIRA" on the left chest 
pocket, shoulder-length wavy black hair, sharp dark eyes, calm intelligent leader. 
DEV = Indian man wearing a black oversized hoodie with a visible name patch reading "DEV" on the chest, black 
rectangular glasses, messy black hair, nervous genius. 
MAYA = Indian woman wearing a beige oversized hoodie with a visible name patch reading "MAYA" on the chest, long 
dark wavy hair, observant and mysterious. 
The name patches must remain visible and readable. 
13 
 
ENVIRONMENT CONSISTENCY: 
Use the exact same underground digital archive facility from all previous scenes. 
Same giant futuristic monitor. 
Same room layout. 
Same circular machine structure. 
Same metallic walls. 
Same blue-white holographic lighting. 
Same atmosphere. 
Same camera quality. 
Do not change locations. 
Do not introduce new environments. 
Everything must match previous scenes exactly. 
VOICE GENERATION PRIORITY: 
Generate real audible speech. 
Every dialogue line must be spoken clearly. 
High volume dialogue. 
No silent characters. 
No narration. 
No subtitles. 
No overlapping voices. 
Perfect lip synchronization. 
Speech must be louder than all background sounds. 
AIRA Voice: 
Female. 
14 
 
Confident. 
Calm. 
Clear pronunciation. 
High volume. 
DEV Voice: 
Male. 
Nervous. 
Fast speaking speed. 
High volume. 
MAYA Voice: 
Female. 
Controlled. 
Mysterious. 
Clear and audible. 
High volume. 
SCENE 4: 
Immediately after the hidden video file appears. 
The video automatically starts playing on the giant monitor. 
The monitor now shows a recording of the same room. 
Inside the recording, three figures are visible. 
The figures are AIRA, DEV, and MAYA. 
They are standing in the same positions. 
The camera remains focused on the shocked faces of the real characters. 
The recorded versions move slightly. 
The real characters freeze. 
The realization slowly hits them. 
DEV takes a step backward. 
15 
 
AIRA stares intensely at the screen. 
MAYA becomes visibly uncomfortable. 
The recorded MAYA suddenly turns toward the camera and smiles unnaturally. 
The smile feels wrong and disturbing. 
Blue monitor light flickers across everyone's faces. 
The tension rises rapidly. 
DIALOGUE TIMING: 
1.5 seconds 
DEV points at the monitor. 
DEV (high volume, shocked): 
"That's us!" 
Pause. 
3.0 seconds 
DEV looks closer at the screen. 
DEV (high volume, frightened): 
"That's literally us!" 
Pause. 
4.2 seconds 
MAYA stares at the smiling version of herself. 
MAYA (high volume, disturbed): 
"That recording shouldn't exist." 
FACIAL EXPRESSIONS: 
DEV = terrified, confused, panicked. 
16 
 
AIRA = serious, analytical, focused. 
MAYA = disturbed, unsettled, suspicious. 
RECORDED MAYA: 
Slow unnatural smile. 
Direct eye contact with the camera. 
Creepy expression. 
No dialogue from the recorded version. 
CAMERA: 
Static medium-wide shot. 
Monitor clearly visible. 
Characters clearly visible. 
No camera movement. 
No scene transition. 
Focus on realistic reactions and lip sync. 
LIGHTING: 
Blue monitor glow. 
Dark sci-fi shadows. 
Flickering screen reflections. 
High tension thriller atmosphere. 
Ultra-realistic cinematic sci-fi thriller. 
Professional acting. 
Natural speech. 
Perfect lip synchronization. 
17 
 
5-second movie scene. 
 
The recording begins playing. 
It shows Aira, Dev, and Maya standing in the same room. 
DEV: That's us. 
DEV: That's literally us. 
MAYA: That recording shouldn't exist. 
Recorded Maya suddenly smiles. 
SCENE 5 (0:20–0:25) 
For Qwen, the biggest fix is to repeat the dialogue ownership rules multiple times. Models sometimes assign lines to 
the wrong character unless you explicitly forbid it. 
SCENE 4 – VIDEO REVEAL 
USE THE EXACT SAME CHARACTER REFERENCE IMAGES. 
Maintain identical faces, hairstyles, clothing, body proportions, age, skin tone, and identity from previous scenes. 
CHARACTER CONSISTENCY: 
AIRA: 
Indian woman. 
Dusty pink tactical jacket. 
Visible name patch reading "AIRA". 
Shoulder-length wavy black hair. 
Calm leader. 
DEV: 
Indian man. 
Black hoodie. 
Visible name patch reading "DEV". 
Black rectangular glasses. 
18 
 
Messy black hair. 
Nervous genius. 
MAYA: 
Indian woman. 
Beige hoodie. 
Visible name patch reading "MAYA". 
Long dark wavy hair. 
Observant and mysterious. 
Do not swap characters. 
Do not change clothing. 
Do not change faces. 
Do not change hairstyles. 
ENVIRONMENT CONSISTENCY: 
Same underground digital archive facility. 
Same giant monitor. 
Same metallic walls. 
Same circular machine structure. 
Same blue-white lighting. 
Same room. 
No location changes. 
No environment changes. 
STRICT DIALOGUE CONTROL: 
Only DEV speaks DEV's dialogue. 
Only AIRA speaks AIRA's dialogue. 
Only MAYA speaks MAYA's dialogue. 
19 
 
Never swap dialogue. 
Never give AIRA's dialogue to DEV. 
Never give DEV's dialogue to MAYA. 
Never give MAYA's dialogue to AIRA. 
Only one character speaks at a time. 
The next character starts speaking only after the previous character finishes. 
No overlapping voices. 
No background speech. 
No extra words. 
No improvisation. 
No narration. 
No subtitles. 
Generate clear audible dialogue. 
VOICE SETTINGS: 
AIRA: 
Female voice. 
Confident. 
Calm. 
Clear pronunciation. 
High volume. 
Medium-fast speed. 
DEV: 
Male voice. 
Nervous. 
Fast speaking speed. 
High volume. 
Slight panic. 
20 
 
MAYA: 
Female voice. 
Controlled. 
Mysterious. 
High volume. 
Slightly slower speed. 
SCENE DESCRIPTION: 
The hidden video begins playing automatically. 
The monitor now shows a recording of the same room. 
Inside the recording are three people. 
The recording becomes clearer. 
The figures are revealed to be AIRA, DEV, and MAYA. 
The real characters stare at the screen. 
The room becomes silent. 
Blue monitor light reflects across their faces. 
The recorded versions are standing in exactly the same positions as the real versions. 
The realization slowly hits them. 
DEV looks terrified. 
AIRA becomes intensely focused. 
MAYA feels deeply unsettled. 
The recorded MAYA slowly turns her head toward the camera. 
A disturbing smile appears on her face. 
The smile should feel unnatural. 
The tension rises dramatically. 
DIALOGUE ORDER: 
21 
 
FIRST SPEAKER: 
DEV ONLY. 
DEV turns toward the monitor. 
DEV speaks loudly. 
DEV: 
"That's us." 
After DEV finishes speaking, pause briefly. 
SECOND SPEAKER: 
AIRA ONLY. 
AIRA keeps staring at the monitor. 
AIRA speaks loudly. 
AIRA: 
"No one recorded this." 
After AIRA completely finishes speaking, pause briefly. 
THIRD SPEAKER: 
MAYA ONLY. 
MAYA continues looking at the smiling version of herself. 
MAYA speaks loudly. 
MAYA: 
"That recording shouldn't exist." 
After MAYA finishes speaking, no one else speaks. 
END OF DIALOGUE. 
LIP SYNC RULES: 
When DEV speaks: 
Only DEV's lips move. 
22 
 
AIRA and MAYA remain silent. 
When AIRA speaks: 
Only AIRA's lips move. 
DEV and MAYA remain silent. 
When MAYA speaks: 
Only MAYA's lips move. 
DEV and AIRA remain silent. 
No character should mouth another character's dialogue. 
CAMERA: 
Static medium shot. 
Monitor visible. 
All three characters visible. 
No camera movement. 
No camera shake. 
Focus on facial reactions. 
Focus on lip synchronization. 
LIGHTING: 
Strong blue monitor glow. 
Dark sci-fi shadows. 
Flickering screen reflections. 
Suspenseful thriller atmosphere. 
Ultra-realistic cinematic sci-fi thriller. 
Professional acting. 
Perfect lip synchronization. 
23 
 
Clear audible speech. 
High dialogue volume. 
5-second movie scene. 
A further trick: put the dialogue in ALL CAPS if Qwen keeps ignoring it: 
• DEV: "THAT'S US."  
• AIRA: "NO ONE RECORDED THIS."  
• MAYA: "THAT RECORDING SHOULDN'T EXIST."  
Some video models give more weight to uppercase dialogue. 
 
A distorted voice echoes from the recording. 
VOICE: Run. 
AIRA: That was my voice. 
AIRA: But I didn't say it. 
 
DEV: It showed me before I moved. 
MAYA: It's not recording us. 
MAYA: It's ahead of us. 
SCENE 6 (0:25–0:30) 
SCENE 6 – THE SHADOW IN THE RECORDING 
NETFLIX STYLE CINEMATIC THRILLER 
CHARACTER CONSISTENCY (MANDATORY): 
Use the exact same uploaded reference images. 
24 
 
AIRA: 
Indian woman. 
Dusty pink tactical jacket. 
Visible badge reading "AIRA". 
Same face as previous scenes. 
Same hairstyle. 
Same body proportions. 
DEV: 
Indian man. 
Black hoodie. 
Visible badge reading "DEV". 
Black rectangular glasses. 
Same face as previous scenes. 
MAYA: 
Indian woman. 
Beige hoodie. 
Visible badge reading "MAYA". 
Same face as previous scenes. 
Same hairstyle. 
Do not morph faces. 
Do not merge identities. 
Do not change clothing. 
Do not change badges. 
ENVIRONMENT CONSISTENCY: 
Same underground digital archive facility. 
Same giant monitor wall. 
Same circular machine structure. 
Same metallic walls. 
Same blue-white holographic lighting. 
25 
 
Same room layout. 
No location changes. 
No environment changes. 
REALISM REQUIREMENTS: 
Photorealistic humans. 
Netflix original series quality. 
Realistic facial muscles. 
Realistic eye movement. 
Realistic breathing. 
Realistic skin texture. 
No cartoon style. 
No anime style. 
No artificial face distortion. 
STRICT SPEAKER CONTROL: 
Only the assigned character may speak. 
No dialogue swapping. 
No overlapping voices. 
No background voices. 
No narration. 
No subtitles. 
No improvised dialogue. 
Only the exact script below may be spoken. 
When one character speaks, only that character's lips move. 
26 
 
TIMELINE: 
0.0s – 1.2s 
The recording continues the giant monitor. 
A dark silhouette appears behind the recorded versions of AIRA, DEV, and MAYA. 
The silhouette has no visible face. 
No visible eyes. 
The room becomes silent. 
DEV notices the figure first. 
1.2s – 2.2s 
DEV ONLY SPEAKS 
DEV 
(high volume, frightened, fast speech): 
"Tell me that's not behind us." 
Only DEV's lips move. 
AIRA and MAYA remain completely silent. 
Pause 0.3 seconds. 
2.5s – 3.6s 
AIRA ONLY SPEAKS 
AIRA 
(calm, firm, high volume): 
"If it was behind us..." 
Only AIRA's lips move. 
Pause 0.2 seconds. 
3.8s – 4.4s 
27 
 
AIRA CONTINUES 
AIRA 
(firm, confident): 
"We'd already know." 
Only AIRA's lips move. 
Pause 0.2 seconds. 
4.5s – 5.0s 
MAYA ONLY SPEAKS 
MAYA 
(slow, observant, high volume): 
"Look closer." 
Immediately after MAYA speaks, the monitor flashes: 
YOU HAVE SEEN IT 
END SCENE 
VOICE MODULATION: 
DEV: 
Male. 
Panic. 
Fast speed. 
High volume. 
AIRA: 
Female. 
Calm. 
Leader-like. 
Medium speed. 
High volume. 
MAYA: 
Female. 
28 
 
Mysterious. 
Slow speed. 
High volume. 
CAMERA: 
Static medium-wide shot. 
Monitor visible. 
All three characters visible. 
No camera movement. 
Focus on facial reactions. 
Focus on lip synchronization. 
LIGHTING: 
Strong blue monitor glow. 
Dark cinematic shadows. 
Screen flicker reflections. 
High tension atmosphere. 
Ultra-realistic Netflix-style sci-fi thriller. 
Perfect lip synchronization. 
Clear audible speech. 
Professional acting. 
5-second movie scene. 
 
A dark silhouette appears inside the recording. 
DEV: Tell me that's not behind us. 
AIRA: If it was behind us... 
29 
 
AIRA: We'd already know. 
MAYA: Look closer. 
MAYA: It has no reflection. 
SCREEN: YOU HAVE SEEN IT 
SCENE 7 (0:30–0:35) NOW IT CAN SEE YOU 
NETFLIX ORIGINAL STYLE SCI-FI THRILLER 
CHARACTER CONSISTENCY (MANDATORY): 
Use the exact same reference images from all previous scenes. 
AIRA: 
Indian woman. 
Dusty pink tactical jacket. 
Visible badge reading "AIRA". 
Same face. 
Same hairstyle. 
DEV: 
Indian man. 
Black hoodie. 
Visible badge reading "DEV". 
Black rectangular glasses. 
Same face. 
MAYA: 
Indian woman. 
Beige hoodie. 
Visible badge reading "MAYA". 
Same face. 
Same hairstyle. 
Do not morph faces. 
Do not alter badges. 
30 
 
Do not change clothing. 
Do not change identity. 
REALISM: 
Photorealistic humans. 
Netflix-quality cinematography. 
Real-world lighting. 
Natural human movement. 
Natural facial expressions. 
Natural breathing. 
No cartoon appearance. 
No anime style. 
ENVIRONMENT CONSISTENCY: 
Same underground digital archive facility. 
Same giant monitor wall. 
Same circular machine structure. 
Same metallic walls. 
Same blue-white monitor glow. 
Same room layout. 
No location changes. 
STRICT SPEAKER CONTROL: 
Only the assigned character may speak. 
No dialogue swapping. 
No extra dialogue. 
31 
 
No narration. 
No subtitles. 
No overlapping voices. 
One speaker at a time. 
Only the speaking character's lips move. 
DIALOGUE TIMELINE: 
0.0s – 1.0s 
The giant monitor glitches violently. 
The words appear: 
"NOW IT CAN SEE YOU" 
The text fills the entire monitor. 
Blue light flashes across the room. 
All three characters stare at the screen. 
Nobody speaks. 
1.0s – 2.1s 
DEV ONLY SPEAKS 
DEV 
(high volume, frightened, fast speech): 
"It knows we're watching." 
Only DEV's lips move. 
AIRA and MAYA remain silent. 
Pause 0.3 seconds. 
2.4s – 3.5s 
AIRA ONLY SPEAKS 
32 
 
AIRA 
(calm, serious, high volume): 
"It's watching us." 
Only AIRA's lips move. 
Pause 0.3 seconds. 
3.8s – 5.0s 
MAYA ONLY SPEAKS 
MAYA 
(slow, observant, high volume): 
"It's learning from us." 
Only MAYA's lips move. 
After MAYA finishes speaking, the monitor flashes again. 
New text appears: 
TURN AROUND 
END SCENE. 
VOICE SETTINGS: 
DEV: 
Male. 
Fearful. 
Fast pace. 
High volume. 
AIRA: 
Female. 
Confident. 
Controlled. 
Medium pace. 
High volume. 
33 
 
MAYA: 
Female. 
Mysterious. 
Observant. 
Slow pace. 
High volume. 
CAMERA: 
Static medium-wide shot. 
Monitor visible. 
All three characters visible. 
No camera movement. 
Focus on realistic reactions. 
Focus on perfect lip synchronization. 
LIGHTING: 
Strong blue monitor glow. 
Dark cinematic shadows. 
Screen flicker reflections. 
Netflix-style sci-fi thriller atmosphere. 
Ultra-realistic. 
Professional acting. 
Perfect lip sync. 
Clear audible speech. 
No voice clash. 
5-second movie scene. 
 
34 
 
SCREEN: NOW IT CAN SEE YOU 
DEV: It knows we're watching. 
AIRA: It's watching us. 
MAYA: It's learning. 
MAYA: Every time we react. 
SCREEN: TURN AROUND 
SCENE 8 (0:35–0:40) 
The issue is that Qwen is trying to do too many things in 5 seconds. A better strategy is to make the dialogue 
ownership impossible to misunderstand. 
Instead of saying "DEV speaks," use Speaker Lock Mode and assign exact timestamps. 
SCENE 8 – THE CORRIDOR OPENS 
SPEAKER LOCK MODE ENABLED 
CRITICAL RULE: 
Only one character is allowed to speak during each time segment. 
If the current speaker is DEV, AIRA and MAYA must remain completely silent. 
If the current speaker is AIRA, DEV and MAYA must remain completely silent. 
If the current speaker is MAYA, DEV and AIRA must remain completely silent. 
No extra dialogue. 
No improvised dialogue. 
No voice overlap. 
No narration. 
No subtitles. 
No dialogue changes. 
35 
 
Use dialogue exactly as written. 
CHARACTER LOCK: 
AIRA: 
Dusty pink tactical jacket. 
Badge says "AIRA". 
DEV: 
Black hoodie. 
Badge says "DEV". 
MAYA: 
Beige hoodie. 
Badge says "MAYA". 
Do not change faces. 
Do not change hairstyles. 
Do not change clothing. 
Do not morph identities. 
BRIDGE FROM SCENE 7: 
Scene begins immediately after the monitor displays: 
TURN AROUND 
The room suddenly loses power. 
The giant monitor goes black. 
Emergency lights activate. 
A hidden metal wall slides open. 
A previously unseen corridor is revealed. 
None of the characters recognize this place. 
The corridor should feel ancient, abandoned, and secret. 
36 
 
TIMELINE: 
[0.0s – 1.5s] 
NO DIALOGUE. 
The wall opens. 
The corridor is revealed. 
Red emergency lights flash. 
A distant metallic sound echoes. 
DEV slowly looks behind him. 
He becomes nervous. 
[1.5s – 2.4s] 
SPEAKER LOCK = DEV ONLY 
DEV: 
"What if we should turn around?" 
Only DEV's lips move. 
AIRA and MAYA remain silent. 
DEV starts turning his body. 
[2.4s – 3.4s] 
SPEAKER LOCK = AIRA ONLY 
AIRA immediately grabs DEV's wrist. 
AIRA: 
"Don't." 
Only AIRA's lips move. 
DEV freezes. 
MAYA remains silent. 
37 
 
[3.4s – 5.0s] 
SPEAKER LOCK = MAYA ONLY 
Camera focuses on MAYA. 
MAYA looks at DEV. 
Then looks toward the dark corridor. 
MAYA: 
"It's communicating." 
Only MAYA's lips move. 
Nobody else speaks. 
ENDING: 
A dark shadow briefly crosses the far end of the corridor. 
The characters do not see it. 
The audience sees it. 
Cut to black. 
VOICE SETTINGS: 
DEV: 
Male. 
Fearful. 
Fast. 
High volume. 
AIRA: 
Female. 
Firm. 
Commanding. 
High volume. 
MAYA: 
Female. 
38 
 
Quiet. 
Disturbed. 
High volume. 
VISUAL STYLE: 
Netflix sci-fi horror. 
Ultra-realistic humans. 
Professional acting. 
Realistic eyes. 
Realistic breathing. 
Perfect lip synchronization. 
Clear audible dialogue. 
No voice clash. 
5-second cinematic scene. 
One more trick: put "SPEAKER LOCK MODE ENABLED" near the top. Some video models respond better to repeated 
hard constraints than to long descriptive paragraphs. 
 
DEV: What if we should? 
DEV: What if it's actually there? 
AIRA: Don't. 
AIRA: That's exactly what it wants. 
SCREEN: AIRA IS CORRECT 
MAYA: It's communicating. 
SCREEN: I REMEMBER YOU 
SCENE 9 (0:40–0:45) 
39 
 
If no voice is being generated at all, the problem is usually not the script. Many video models prioritize visuals and 
silently ignore dialogue. 
Try adding a VOICE GENERATION BLOCK at the very top of every prompt: 
CRITICAL AUDIO INSTRUCTION: 
 
Generate audible spoken dialogue. 
 
Dialogue must be spoken out loud. 
 
Do not use silent acting. 
 
Do not use mute characters. 
 
Do not use text-only communication. 
 
Do not replace speech with facial expressions. 
 
Generate real human voices. 
 
Generate synchronized lip movement. 
 
Generate clear audible dialogue at high volume. 
 
Every line written in quotation marks must be spoken aloud exactly as written. 
 
Speech is mandatory. 
 
Audio is mandatory. 
 
Voice generation is mandatory. 
 
Do not create a silent video. 
Also simplify Scene 9. Too many instructions can cause Qwen to ignore speech. 
Use only this dialogue block: 
40 
 
0.0s - 1.5s 
No speech. 
 
1.5s - 2.5s 
MAYA ONLY: 
 
"I've seen this place before." 
 
2.7s - 3.7s 
AIRA ONLY: 
 
"That's impossible." 
 
3.9s - 5.0s 
DEV ONLY: 
 
"Then why is your name on the wall?" 
And add this directly underneath: 
AUDIO PRIORITY RULE: 
 
1. Generate speech first. 
2. Generate lip sync second. 
3. Generate visuals third. 
 
If a choice must be made, prioritize dialogue over visual effects. 
 
Every quoted sentence must be spoken clearly. 
 
Do not skip dialogue. 
 
SCREEN: BUT YOU DON'T REMEMBER ME 
Memory fragments flash. 
MAYA: I've seen this. 
41 
 
MAYA: This exact room. 
AIRA: We weren't brought here. 
AIRA: We came here. 
DEV: Oh my God. 
DEV: We did this. 
SCREEN: RESTORE MEMORY? 
SCENE 10 (0:45–0:50) 
Since Scene 9 ends with "MAYA WAS HERE" and "DO NOT RESTORE MEMORY", Scene 10 should be the turning point 
where the characters realize they may have erased their own memories. This is where the mystery becomes 
personal. 
SCENE 10 – THE MEMORY CHAMBER 
DIALOGUE ACCURACY IS ABSOLUTE PRIORITY. 
 
EVERY CHARACTER MUST SPEAK THEIR EXACT DIALOGUE. 
 
NO SILENT VIDEO. 
 
NO DIALOGUE SWAPPING. 
 
NO VOICE OVERLAP. 
 
ONLY THE SPEAKING CHARACTER MAY MOVE THEIR LIPS. 
 
ALL OTHER CHARACTERS REMAIN SILENT. 
 
CHARACTER CONSISTENCY LOCKED: 
 
AIRA: 
Pink tactical jacket. 
Visible badge "AIRA". 
42 
 
 
DEV: 
Black hoodie. 
Black glasses. 
Visible badge "DEV". 
 
MAYA: 
Beige hoodie. 
Visible badge "MAYA". 
 
Maintain exact faces. 
 
Maintain exact hairstyles. 
 
Maintain exact clothing. 
 
Maintain exact body proportions. 
 
No morphing. 
 
No face distortion. 
 
No identity changes. 
 
AUTHENTIC ENVIRONMENT: 
 
Continue directly from Scene 9. 
 
The hidden door from the corridor slowly opens. 
 
Behind it is a forgotten MEMORY CHAMBER. 
 
This room has never been seen before. 
 
Large circular room. 
 
Metallic architecture. 
43 
 
 
Ancient futuristic technology. 
 
Blue-white holographic light. 
 
Floating digital fragments. 
 
Broken memory storage units. 
 
Dust particles floating in the air. 
 
The room feels abandoned for years. 
 
Yet the systems are still running. 
 
The audience should immediately feel: 
 
"We were here before." 
 
SCENE ACTION: 
 
The chamber door opens with a deep metallic sound. 
 
AIRA enters first. 
 
DEV follows carefully. 
 
MAYA remains frozen near the entrance. 
 
The holographic displays suddenly activate. 
 
Memory fragments begin floating around them. 
 
Quick flashes appear: 
 
AIRA typing commands. 
 
44 
 
DEV arguing with someone unseen. 
 
MAYA crying. 
 
The flashes are brief. 
 
The room recognizes them. 
 
A circular console activates in the centre. 
 
Large text appears: 
 
AUTHORIZED USERS DETECTED 
 
The three characters stare in shock. 
 
TIMELINE: 
 
0.0s – 1.0s 
 
No dialogue. 
 
Door opens. 
 
Characters enter. 
 
Memory chamber activates. 
 
Blue holographic light fills room. 
 
1.0s – 2.0s 
 
ONLY DEV SPEAKS. 
 
Volume: High. 
 
Emotion: Fear and disbelief. 
45 
 
 
Speed: Fast. 
 
DEV: 
 
"What if we're helping it?" 
 
Only DEV lips move. 
 
AIRA and MAYA remain silent. 
 
Pause. 
 
2.2s – 3.3s 
 
ONLY MAYA SPEAKS. 
 
Volume: High. 
 
Emotion: Disturbed. 
 
Speed: Slow and controlled. 
 
MAYA: 
 
"It's giving us a choice." 
 
Only MAYA lips move. 
 
Pause. 
 
3.5s – 4.8s 
 
ONLY AIRA SPEAKS. 
 
Volume: High. 
 
46 
 
Emotion: Determined. 
 
Speed: Medium. 
 
AIRA: 
 
"If someone erased our memories..." 
 
Pause 0.2 seconds. 
 
AIRA continues: 
 
"Then the truth is worth remembering." 
 
Only AIRA lips move. 
 
FINAL TWIST: 
 
The central console suddenly activates. 
 
A glowing button appears. 
 
RESTORE MEMORY 
 
YES      NO 
 
The button pulses slowly. 
 
The room becomes silent. 
 
All three characters stare at it. 
 
A distant distorted voice whispers: 
 
"Choose." 
 
The voice is not human. 
47 
 
 
Cut to black. 
 
AUDIO RULES: 
 
Generate real human voices. 
 
High volume. 
 
Clear speech. 
 
Perfect lip synchronization. 
 
One speaker at a time. 
 
No voice clash. 
 
No skipped dialogue. 
 
VISUAL STYLE: 
 
Netflix original sci-fi thriller. 
 
Ultra-realistic humans. 
 
Smooth animation. 
 
Natural walking. 
 
Natural facial expressions. 
 
Professional acting. 
 
Cinematic lighting. 
 
High tension. 
48 
 
 
5-second movie scene. 
Character Dialogue Only 
DEV (fearful, fast, high volume) 
"What if we're helping it?" 
MAYA (disturbed, slow, high volume) 
"It's giving us a choice." 
AIRA (determined, firm, high volume) 
"If someone erased our memories... then the truth is worth remembering." 
This scene works because it changes the setting, reveals a new room, confirms the characters were connected to the 
facility, and ends with a major decision that leads directly into Scene 11. 
 
SCREEN: YES / NO 
DEV: What if that's exactly what it wants? 
DEV: What if we're helping it? 
 
MAYA: It's giving us a choice. 
AIRA: If someone erased our memories... 
AIRA: Then the truth is worth remembering. 
Aira presses YES. 
SCENE 11 – THE TRUTH RETURNS 
DURATION: 5 SECONDS 
CONTINUATION FROM SCENE 10 
The scene begins immediately after the holographic message glitches. 
49 
 
The words: 
MEMORY BACKUP FOUND 
RESTORATION COMPLETE 
remain floating above the central console. 
The Memory Chamber suddenly becomes brighter. 
Thousands of memory fragments explode into motion around the room. 
Blue holographic particles swirl through the air. 
The entire chamber feels alive. 
CHARACTER CONSISTENCY: 
AIRA: 
 
 
Dusty pink tactical jacket. 
 
 
Visible badge: AIRA. 
DEV: 
Black tactical jacket 
Visible badge: DEV. 
Black rectangular glasses. 
MAYA: 
Beige tactical jacket. 
Visible badge: MAYA. 
Maintain exact faces. 
50 
 
Maintain exact hairstyles. 
Maintain exact clothing. 
No morphing. 
No distortion. 
ENVIRONMENT: 
Same Memory Chamber. 
Floating holographic memories. 
Blue-white light. 
Reflective metallic floor. 
Fog near floor. 
Broken memory pods. 
The chamber now looks fully activated. 
Memory fragments float everywhere. 
The audience can see brief flashes: 
AIRA discovering ARCHIVE-0. 
DEV hacking security systems. 
MAYA hiding evidence. 
Government agents entering the facility. 
Emergency lockdown. 
CAMERA MOVEMENT: 
0.0s – 0.8s 
Wide cinematic shot. 
Camera slowly orbits around AIRA, DEV, and MAYA. 
51 
 
Memory fragments fly around them. 
The room glows brighter. 
Nobody speaks. 
0.8s – 1.8s 
Smooth push-in toward DEV. 
Close-up. 
Reflections of memories visible in his glasses. 
Shock appears on his face. 
ONLY DEV SPEAKS. 
DEV 
Volume: Very High 
Emotion: Realization 
Speed: Fast 
Dialogue: 
"We weren't trapped here." 
Only DEV lips move. 
AIRA silent. 
MAYA silent. 
1.8s – 3.0s 
Camera smoothly pans toward MAYA. 
Close-up. 
Tears forming in eyes. 
She finally remembers. 
52 
 
ONLY MAYA SPEAKS. 
MAYA 
Volume: High 
Emotion: Emotional realization 
Speed: Medium 
Dialogue: 
"We came back." 
Only MAYA lips move. 
Nobody else speaks. 
3.0s – 4.2s 
Low-angle cinematic close-up on AIRA. 
Blue holographic light reflects in her eyes. 
She remembers everything. 
Strong determined expression. 
ONLY AIRA SPEAKS. 
AIRA 
Volume: Very High 
Emotion: Powerful and confident 
Speed: Medium 
Dialogue: 
"To finish what we started." 
Only AIRA lips move. 
Nobody else speaks. 
53 
 
4.2s – 5.0s 
CLIMAX MOMENT 
Camera rapidly reveals memory flashes around the room: 
AIRA recording a warning. 
DEV sealing ARCHIVE-0. 
MAYA hiding the final file. 
All three voluntarily erasing their memories. 
The final memory appears: 
RECORDED AIRA: 
"If you're seeing this... you finally remembered." 
The transmission door unlocks. 
Brilliant white light floods the chamber. 
Large holographic text appears: 
TRUTH READY FOR TRANSMISSION 
Camera slowly pushes toward the open doorway. 
Cut to black. 
AUDIO RULES: 
Generate clear human voices. 
Very high volume. 
No voice overlap. 
No voice clash. 
One speaker at a time. 
Perfect lip synchronization. 
54 
 
Every line must be spoken exactly as written. 
VISUAL RULES: 
Smooth camera movement. 
Natural breathing. 
Natural blinking. 
Realistic eye movement. 
Professional acting. 
Netflix sci-fi thriller quality. 
Bridge directly into Scene 12. 
 
Memories flood back. 
RECORDED AIRA: If this reaches the public... 
RECORDED AIRA: They can't hide it. 
RECORDED DEV: What if they find us first? 
MAYA: They found us. 
MAYA: They erased us. 
AIRA: We were never trapped here. 
AIRA: We came back for the file. 
SCENE 12 – FINAL TRANSMISSION 
Camera & Dialogue Timeline 
0.0s – 1.2s 
CAMERA: 
55 
 
• Wide cinematic shot.  
• Camera enters the massive Transmission Hall from behind AIRA, DEV, and MAYA.  
• All three characters are visible in the same frame.  
• Giant holographic screens illuminate the room.  
• Blue-white light reflects on their faces.  
• Camera slowly pushes forward.  
NO DIALOGUE 
The audience takes in the scale of the room. 
1.2s – 2.2s 
CAMERA: 
• Slow push-in toward AIRA.  
• DEV and MAYA remain visible behind her.  
• Keep all three characters in frame.  
ONLY AIRA SPEAKS 
AIRA 
(high volume, emotional, determined) 
"They erased our memories." 
Only AIRA moves her lips. 
DEV and MAYA remain silent. 
2.2s – 3.2s 
CAMERA: 
• Smooth pan right toward DEV.  
• AIRA remains partially visible.  
56 
 
• MAYA remains visible in background.  
• No camera cuts.  
ONLY DEV SPEAKS 
DEV 
(high volume, confident) 
"But they couldn't erase the truth." 
Only DEV moves his lips. 
AIRA and MAYA silent. 
3.2s – 4.2s 
CAMERA: 
• Smooth pan toward MAYA.  
• All three remain visible.  
• Focus slightly stronger on MAYA.  
ONLY MAYA SPEAKS 
MAYA 
(high volume, emotional but hopeful) 
"The world deserves to know." 
Only MAYA moves her lips. 
4.2s – 5.0s 
GRAND FINALE 
CAMERA: 
• Camera slowly rises above all three characters.  
• All three stand together facing the central console.  
57 
 
• AIRA presses UPLOAD TO WORLD.  
Massive holographic screens activate. 
Global data streams explode across the room. 
World map appears. 
Upload reaches: 
100% 
Large text appears: 
UPLOAD COMPLETE 
The blue light fills the entire hall. 
All three characters stand side by side. 
No one speaks. 
AIRA looks at DEV. 
DEV looks at MAYA. 
MAYA smiles slightly. 
For the first time in the entire film, they look at peace. 
The camera slowly pulls backward. 
The facility fades into darkness. 
Final screen: 
THE TRUTH SURVIVED 
Fade to black. 
Dialogue Only 
AIRA: 
"They erased our memories." 
58 
 
DEV: 
"But they couldn't erase the truth." 
MAYA: 
"The world deserves to know." 
 
SCREEN: UPLOAD TO WORLD 
AIRA: They took our memories. 
AIRA: But they couldn't erase the truth. 
DEV: We finish what we started. 
MAYA: The world deserves to know. 
Aira presses UPLOAD TO WORLD. 
SCREEN: UPLOAD COMPLETE 
MAYA: Now they remember. 
           END 
 
 
:BY-TANYA GUPTA 
                                                            
