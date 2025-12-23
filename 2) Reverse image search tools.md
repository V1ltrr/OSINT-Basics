# Reverse image search tools — OSINT (Person identification)
Tools and search techniques focused on identifying people, tracking digital footprints, and linking images to online identities.  
These methods are commonly used in OSINT investigations to verify identities, detect fake profiles, or map a person’s online presence.

---

## General reverse image search engines
Broad search engines useful as a first step to locate reused profile pictures across multiple platforms.

- ``targeted_keyword site:images.google.com`` ― find websites, social networks, and articles where a person’s photo appears  

- ``targeted_keyword site:yandex.com/images`` ― powerful facial matching, often returns social media profiles and less-indexed websites  

- ``targeted_keyword site:bing.com/images`` ― locate similar face images and linked web pages for cross-verification  

---

## Face recognition focused tools
Specialized platforms designed specifically to identify people using facial recognition.

- ``targeted_face site:pimeyes.com`` ― find appearances of a person across the web using facial recognition  

- ``targeted_face site:facecheck.id`` ― identify people across multiple public sources and indexed databases  

- ``targeted_face site:socialcatfish.com`` ― verify identities and detect fake or impersonated profiles  

---

## Exact match & image reuse detection
Tools useful for detecting stolen or recycled profile pictures.

- ``targeted_image site:tineye.com`` ― track exact matches and identify the earliest publication of an image  

---

## Social media profile discovery
Manual OSINT techniques to locate social media accounts using reused images.

- ``targeted_keyword site:facebook.com`` ― search for reused profile pictures or public images on Facebook  

- ``targeted_keyword site:instagram.com`` ― identify accounts using the same profile image  

- ``targeted_keyword site:linkedin.com/in`` ― find professional profiles using the same or similar photo  

- ``targeted_keyword site:vk.com`` ― useful for Eastern European profiles and image reuse across platforms  

---

## File-based image leaks
Useful to find profile pictures stored in documents or leaked archives.

- ``targeted_keyword filetype:jpg OR filetype:png`` ― locate publicly accessible images  

- ``targeted_keyword filetype:pdf`` ― find documents containing profile photos (CVs, reports, presentations)  

---

## Techniques

- Crop the image to focus only on the face before searching  
- Run the same image across multiple engines (results vary significantly)  
- Look for repeated usernames, bios, or background elements  
- Cross-reference image results with social networks and public records  
- Combine image results with name, location, or employer keywords  
