<img width="128" height="48" alt="QR Mii" src="https://github.com/user-attachments/assets/95a0d095-4177-42da-a53a-dc71efbc9996" />
<p>This is a project where you can make Mii QR Codes from your wii</p>
<hr>
<h2>Step 1</h2>
<p>Download the latest release (The zip file under Assets) <a href="https://github.com/funkymonkeyhen/qr-mii/releases/download/beta/qr-mii.zip"> or click here</a></p>
<h2>Step 2</h2>
<p>Extract the zip file</p>
<h2>Step 3</h2>
<p>Move files in the apps folder to the apps folder on the root of your Wii's SD Card (Create one if there is none)</p>
<h2>Step 4</h2>
<p>Put the SD Card in your Wii and open the app in the Homebrew channel</p>
<h2>Step 5</h2>
<p>Select your Mii by pressing A on your Wiimote</p>
<h2>Step 6</h2>
<p>Scan the QR Code With Your NDS,3DS,WiiU, or Switch2Camera</p>
<h2>Optional</h2>
<p>If Saving the QR Code dosn't work just scan it with your phone and use that to save the qr code</p>
<hr>
<h2>Screenshots</h2>
<img alt="working with 3ds" src="screenshots/IMG_20260919_114911_432.jpg" />
<img alt="working with switch2" src="screenshots/IMG_20260919_115239_475.jpg" />
<img alt="selection screen" src="screenshots/WIN_20260919_11_56_53_Pro.jpg" />
<img alt="Created Qr Code Screen" src="screenshots/WIN_20260919_11_57_19_Pro.jpg" />
<img alt="saved to sd card" src="screenshots/saved.jpg" />
<p></p>Third-party code included</p>
`source/qrcodegen.c/h` - Nayuki's QR Code generator library (MIT license).
This is the same QR library used by the MiiPort homebrew project.
`source/aes.c/h` - tiny-AES-c (public domain / Unlicense), used only for
its raw AES-128 block primitive; the actual CCM logic on top of it is
hand-written to match the 3DS's specific implementation.
