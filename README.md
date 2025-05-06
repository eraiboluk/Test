# 🎙️ Lip Sync 3D Characters in Unity (FREE)

Add realistic lip sync animation to your 3D characters using **Blender**, **Unity**, and the **uLipSync** plugin — all for free! This tutorial walks you through step-by-step how to create shape keys, export from Blender, and set up lip syncing in Unity with free tools.

---

## 📸 Thumbnail
![Lip Sync Characters in Unity (FREE)](./A_thumbnail_for_a_tutorial_video_showcases_a_3D-re.png)

---

## 📹 Video Tutorial
Watch the full tutorial on YouTube: [**Lip Sync Characters in Unity (FREE)**]([#](https://youtu.be/zr0yyhkiwR8))  

---

## 🛠 Features

- 🎨 3D character modeling in Blender
- 🗣️ Shape Key creation for A, E, I, O, U phonemes
- 💻 Exporting and importing between Blender and Unity
- 🔌 Integrating the free uLipSync plugin
- 🦷 Syncing teeth and lips blend shapes
- ✅ Real-time voice-to-animation playback

---

## 🧰 Tools Used

- [Blender](https://www.blender.org/)
- [Unity](https://unity.com/)
- [MakeHuman](http://www.makehumancommunity.org/)
- [uLipSync Plugin (Free)](https://github.com/hecomi/uLipSync)

---

## 🧪 How It Works

1. **Create or Import Character in Blender**
   - Use MakeHuman or your own rigged character
   - Add shape keys for A, E, I, O, U
   - Create matching shape keys for teeth mesh

2. **Export as FBX**
   - Apply all modifiers
   - Set *Path Mode* to `Copy` and embed textures

3. **Import to Unity**
   - Extract and assign textures
   - Verify blend shapes are visible under `SkinnedMeshRenderer`

4. **Setup uLipSync**
   - Add `uLipSyncBlendShape` to the character
   - Link blend shapes
   - Add audio + phoneme profile

5. **Sync Teeth**
   - Use custom script to mimic lip shapes on teeth mesh
