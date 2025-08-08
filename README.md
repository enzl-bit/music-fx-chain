# 🎧 Music VST Presets for Listening

This repository contains optimized VST chain presets for enhancing music listening using [Equalizer APO](https://sourceforge.net/projects/equalizerapo/) and [ReaPlugs VST FX Suite](https://www.reaper.fm/reaplugs/).

## 📂 Included Presets

- `music_listening_chain.rfxchain` – REAPER FX chain preset
- `music_listening_chain.vsthost` – Preset file for VSTHost

## 🛠 Recommended FX Chain

1. ReaXComp (Multiband Compression)
2. ReaEQ (Equalizer)
3. ReaComp (Compressor)
4. ReaGate (Noise Gate)
5. JS: Stereo Enhancer  
   - Width Low: 1.00  
   - Width High: 1.22  
   - Crossover: 250Hz  

## 🚀 How to Use

### With VSTHost
1. Download and install [VSTHost](https://www.hermannseib.com/english/vsthost.htm)
2. Open `music_listening_chain.vsthost`
3. Load the corresponding VST plugins (ensure they're installed)

### With REAPER
1. Install REAPER or [ReaPlugs](https://www.reaper.fm/reaplugs/)
2. Load `music_listening_chain.rfxchain` in the FX chain window

### With Equalizer APO
1. Use the [VST Plugin](https://sourceforge.net/p/equalizerapo/wiki/Plugins/) feature
2. Load your VSTs in the same chain order as above

## 📢 Tips
- Set stereo enhancer to Wet 100% if you're sure your headphones/speakers are balanced
- Reduce noise by adjusting ReaGate threshold or placing it earlier in the chain
- Fine-tune ReaEQ for your specific headphone/speaker frequency response

---

Feel free to fork, modify, and improve this preset for your listening needs!
