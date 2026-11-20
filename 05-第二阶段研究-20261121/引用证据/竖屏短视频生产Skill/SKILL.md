# Vertical Short Video Production

## Lock the script and timing

- Write the script as a shot list with one row per shot and the narration, picture, camera, light and sound for that shot.

- Keep product facts as placeholders until the user supplies them, and never invent a title, price, specification or efficacy claim.

- Keep the finished film 9:16 vertical.

## Check for an identical delivered file before starting

- Hash every incoming video file with md5 before starting any replica work, and compare the hash against the delivered ledger and the delivered files.

- When the hash matches an already delivered and verified file, return that existing file under a new filename with a short re-verification note, and do no re-render, no re-record and no new generation.

- Render, record or generate only when the hash is new.

- Apply a stop only to the job and the chat the user named, and leave the jobs in other chats running.

## Check the script three times before shooting

- Run pass one on characters and appearances, pass two on time, place, props and action subjects, and pass three on narration, subtitles and picture together, checking the book title character by character, every number and every name.

- Fix the exact product name in writing at project setup, list every name easily confused with it, print both on the writing brief, the mashup draft and the shooting script, scan every draft against the list, and search the full script text for both names before review.

- Check the hook is a moment from the story itself placed in the first seconds in the same place and moment, and do not open with a title card or a different scene.

- Check the first naming of the book against the 60 second deadline, treat 90 seconds only as the average watch reference, and record an exception only when the product is on screen from the first frame and the user confirms the later naming time, as with the wooden box naming at about 70 seconds.

- Follow this 60 second deadline where it conflicts with director-checklist, shuohao-script-storyboard, goal-driven-video-qa-trial and video-captions-cn, because those skills still state a 60 to 90 second window.

- Treat 1:1 as the full film shot by shot with no compression and no story change, and reword the narration enough to avoid duplication while keeping it smooth and storylike.

- Fix every issue found in the three passes before recording narration or generating video, and list the issues fixed.

- Read every script end to end before sending it to the user, and check fluency, logic and cross-film similarity across the whole batch, because a grep checklist alone only proves a line was changed.

- Answer every opening question within the next one or two shots, check repeated lines, skeletons and topics across the batch and rewrite them, giving each repeated topic to one film only, and write the narration in plain spoken vernacular with no classical text except a card opening that reads the quote plus one plain explanation and at most one key quote per film.

- Give every shot narration, keep a flash card to one line per page, at least 3 seconds per page and at most 3 pages, flash only pages whose titles are verified, vary the openings across the batch, and keep card openings to at most 2 or 3 films, with sound and a person or an event in the first 3 to 5 seconds of every film.

## Record narration first

- Split the narration by the storyboard shots before recording, record the full narration verbatim before generating any picture, and keep the recorded files and the request bodies beside them.

- Re-time the script from the measured narration, and trim or extend the picture to the recorded narration instead of slowing the narration.

- Use the same timbre reference for every narration take, run loudness normalisation with absolute paths, parse the last output line as JSON when a batch job prints progress lines first, and never run narration in a detached background shell.

## Pick character voices by listening

- Choose each character voice yourself from the role, and never offer the user a list of voices to pick from.

- Listen to the reference audio for a candidate voice before assigning it, and confirm by ear that its gender and age fit the character.

- Never choose a voice by its name or by a pitch number alone.

- Record a short sample in the character's own lines before changing any voice, and let the user hear the sample first.

- Give every character a distinct voice, and never reuse the narration voice for a character.

## Generate motion from first frames

- Generate a still first and use it as the first frame for image-to-video, drawn in the starting state of the action, and archive every generation prompt verbatim as issued beside the shot it made.

- State Chinese people and Chinese scenes in every image and video prompt, name one clear, slow and small character action plus the camera move, and lock the face and the headdress to the first frame, forbidding makeup, headdress and face shape changes.

- Never put dust, floating particles or light spots in a prompt unless the user asks, keep characters silent for narration films, split any shot longer than about 10 seconds into continuation segments, write head movement in one direction only, and write action in timed stages for action shots.

- Run at most 4 images and 6 videos per round, and run one video round at a time.

- Run one timed single-shot trial before quoting batch time or cost for a new model or route, record the measured seconds per second and the measured cost, and correct the batch estimate in the same message when a measured trial changes it.

## Lock faces with reference stills

- Make one front-face still per character and one still per key prop, pass the character anchor as a face reference for every new segment, verify the face against the anchor at every round, and regenerate when its face drifts.

- Treat a character anchor as locking face and headdress only, and check front-facing frames, because a back view alone cannot prove hair, glasses or face match the fixed look.

## Keep characters and props consistent

- Fix each character in writing before generating shots, state every fixed trait in each generation prompt, anchor each new shot to the previous shot or a saved reference frame, and check hands, rings, jewellery and props in the generated frames.

## Use real product footage for legible product shots

- Never generate a legible product shot with AI, and use the de-subtitled original clip where one exists.

- Where no original clip exists, generate a video shot that fits the narration instead of holding a static product image, because a static crop goes blurry when enlarged to full screen.

- Never run a product image through image-to-video, never enlarge or crop a book clip, and treat a book clip as a fixed length anchor, never cutting, speeding, slowing or padding it with stills.

- Split a speaking shot from the product close up that follows it, never paste a product image into a hand, match the seam with the colour graded original and a look at the calendar before the cut, hold each product page for 2 to 3 seconds, and adjust the chroma of the original shot only when tones mismatch.

- Use real photos of the actual product for book and cover close-ups, and verify book and title text character by character before accepting a shot.

## Drive dialogue with the tested lip sync route

- Drive single person dialogue with u11, cut into 2 to 3 second segments from the same first frame with hard cuts and no dissolves, and split multi-person dialogue into single-person u11 shots instead of routing it through 805.

- Treat 803, U22 and 805 as timbre only routes, because they invent their own muffled speech instead of playing the supplied audio, while u11 plays the supplied audio as recorded.

- Follow this u11 only dialogue route where it conflicts with director-checklist, shuohao-script-storyboard, goal-driven-video-qa-trial and video-captions-cn, and strip the loud built in audio from 804 shots before splicing.

## Leave subtitles to post production

- Deliver the finished film with no burned subtitles plus the narration and a word level SRT draft, carrying the full narration text word for word and timing each card from measured word-level timestamps, never from proportional character counts.

- Keep one card at 22 characters or fewer, run the three track check after the post department burns the subtitles, and remake the shot from a starting-state still when the picture runs ahead of the words.

## Keep every shot alive

- Give every shot a person doing something, never leave a full shot as an empty room or a static scene, and fill the second half of a long empty shot with a person entering or practising.

## Mix audio without end fades

- Never add a fade-out at the end of each shot, add one fade-out only at the end of the finished film, check the start of each shot for burst noise, keep the audio track enabled, and check the audio at the start, middle and end.

## Check seams before splicing

- Compare the last frame of one shot with the first frame of the next shot, use a 0.5 second dissolve only for a small pose or position jump, add a transition shot when the scale jumps with no shared anchor, and keep a human gate for the film.

## Check the finished film shot by shot before delivery

- Compare consecutive frames inside every shot, not single stills, because jitter, frozen tails and drift only show when frames move against each other.

- Check the picture action against the narration at the same second in every shot, and fix the shot or the line when they disagree, because a wrong script or a wrong reference original is no excuse for a mismatch reaching the user.

- Watch every generated shot once for a creepy or wrong read, such as a dark room, lifted wet hair, or a body shape that reads as pregnant, and reshoot the shot when it reads wrong.

- Run silencedetect over the finished film, and fill the narration so no gap between sentences exceeds 0.5 seconds.

- End every film with a spoken sales call to action within 0.5 seconds of the end, and never let the picture outlast the voice by seconds.

- Never use ffmpeg zoompan on a product hold, never deliver a static product image as a product shot, and never reuse a shot verbatim across films or inside one film, reshooting it with a new angle, new props or a new sleeve when the same footage would appear twice.

## Deliver under a new name each time

- Give every new version a new filename and a new link, keep superseded versions as backups with the round in the name, and report a defect plainly with its timestamp and the fix needed.

## Report progress from the disk

- List the finished-shot directory and count the files before reporting how many shots are done, and name the shots that are still missing by number, saying which round will make them.

## Verify before claiming done

- Treat a wrapper reporting done as unproven until the output file itself is checked, confirm the file exists and read its video stream duration, confirm the audio stream is present and audible at the start, middle and end, extract frames at every seam and every shot where a character first appears, and re-verify the whole film after any re-generation or re-splice.

## Available connectors

- Autodl Art connector for narration and generated shots through hosted workflows.

- Use muse.connector_search to find other connectors and muse.skill_search to find related skills.

- If nothing here fits, look on the web for a maintained API or MCP server and set it up with Custom Connectors and MCPs, or build a custom connector.

## Alternatives for better results

- Offer a still image sequence with push and pull movement when generated video keeps breaking a character or a hand, and say plainly that the movement is limited.

- Ask the user to choose between candidate shots when two versions both pass verification but tell the story differently.

- Split a long film into units and verify each unit before splicing, so one bad shot does not force a full re-render.
