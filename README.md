Raspberry Pi’s newest OS (Bookworm) released on December 5, 2023, does not work well with this installation.
For best results, use a Raspberry Pi 4 (not a Raspberry Pi 5) and use the legacy 64-bit OS.
Instructions are in the Important - Please Read file on this repository.

DaVinci now uses GPT-4.

On March 26, 2024, OpenAI updated its billing system to require the pre-purchase of credits in order to use the API for most users.  If you do not pre-purchase credits, you will get an API error.

Feb. 23, 2024 Update - I added an alternative voice to DaVinci that uses OpenAI’s text-to-speech model instead of Amazon Polly.  The alternative file is called DaVinciAltVoice.py.  If you decide to you use this version, you do not need to create an AWS account.  In the rest of the instructions, you can skip “pip3 install boto” and “pip3 install awscli” and all of step 3 for configuring the AWS interface.  Substitute “DaVinciAltVoice.py” for “DaVinci.py” everywhere it appears in the instructions.

I also added an Italian speaking version - DaVinciItalian.py.  To use it, you must follow the additional instructions in the introductory comments in that program.
 

![DaVinci Small](https://user-images.githubusercontent.com/22980908/233852733-088f6053-4a10-4ac4-ac80-babd44125cce.jpg)

<img width="653" alt="1" src="https://user-images.githubusercontent.com/22980908/233854978-c6c8ac2e-517a-4b27-ba74-5b4a9d4827fc.png">
<img width="666" alt="2" src="https://user-images.githubusercontent.com/22980908/233854997-83dadc35-8f91-40ba-9ec1-fc3ca8f80309.png">
<img width="629" alt="3" src="https://user-images.githubusercontent.com/22980908/233855008-2afe4822-924d-4641-95c0-732f716071b8.png">
<img width="646" alt="4" src="https://user-images.githubusercontent.com/22980908/233855013-248d60ae-abe2-4362-9764-5419b5bd1c4d.png">
<img width="661" alt="5" src="https://user-images.githubusercontent.com/22980908/233855023-e81133e3-f7ab-42a0-9607-210c9a93be3a.png">
<img width="649" alt="6" src="https://user-images.githubusercontent.com/22980908/233855035-8a210f62-da3a-4681-bf6d-17c296366e15.png">
<img width="634" alt="7" src="https://user-images.githubusercontent.com/22980908/233855045-844bff6a-6ec3-44b1-9e73-b0f01198d441.png">
<img width="620" alt="8A" src="https://user-images.githubusercontent.com/22980908/233855426-c42cc742-27d5-490f-93cb-abf520f65905.png">
<img width="643" alt="8B" src="https://user-images.githubusercontent.com/22980908/233855434-41cdbe27-4470-4383-823c-2637a99ff788.png">
<img width="503" alt="In10" src="https://user-images.githubusercontent.com/22980908/227273897-05b2aa3b-6a97-4589-a8f7-e9b864377bcc.png">
<img width="531" alt="In11" src="https://user-images.githubusercontent.com/22980908/227273934-d8154a22-8365-44e2-b34a-b5b918fa8015.png">
<img width="481" alt="In12" src="https://user-images.githubusercontent.com/22980908/227273987-69605a3e-5e12-4f5e-8b3e-7ddc633dd68e.png">
