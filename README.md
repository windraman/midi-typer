# 🎹 MIDI Typer v1.0

Developed by **Wahyu Indraman Akman** (windraman@gmail.com)

**MIDI Typer** is a lightweight, standalone Windows audio utility that transforms your standard PC typing keyboard into a global real-time piano instrument. Inspired directly by the native "Typing Keyboard to Piano Keyboard" feature in FL Studio, MIDI Typer runs silently in your background system tray, allowing you to jam, practice scales, or trigger notes across any application on your machine.

---

## ✨ Features

* **Zero Software Dependencies:** Routes directly to the native Windows *Microsoft GS Wavetable Synth*—no DAWs, virtual cables, or loopMIDI installations required.
* **FL Studio Keyboard Layout:** Emulates the exact keyboard-to-piano layout mechanism (white keys on row layers, black keys mapped logically above them).
* **Advanced Context System Tray:** Right-click the custom blue note taskbar tray icon to manually pick from dozens of optimized General MIDI instrument families (Pianos, Guitars, Synths, Strings, Orchestral SFX).
* **Live Global Hotkeys:**
  * `UP / DOWN Arrows` -> Cycle through all 128 General MIDI instrument sounds.
  * `LEFT Arrow` -> Shift instantly to a completely random instrument patch.
  * `RIGHT Arrow` -> Randomize and scramble key mapping layouts (Chaos Mode).
  * `PAGE UP / PAGE DOWN` -> Transpose the grid octave pitch boundaries Up or Down.
  * `ESC Key` -> A global panic button to snap your scale maps back to default FL studio definitions.
* **Focus Safety Lock:** Easily toggle hotkeys off via the tray icon menu to safely type out documents, scripts, or emails without accidentally triggering sound shifts or octave boundaries.

---

## 🎹 Keyboard Layout

```text
Black Keys:                          
White Keys:   [Q] [W] [E] [R] [T] [Y] [U] [I] [O] [P] [[]
-----------------------------------------------------------
Black Keys:     [S] [D]     [G] [H] [J]     [L] [;]
White Keys:   [Z] [X] [C] [V] [B] [N] [M] [,] [.] [/] [']
```

---

## 🚀 Installation

1. Go to the **Releases** section of this GitHub repository.
2. Download the compressed file package `MIDI_Typer_v1.0.zip`.
3. Extract the contents and double-click `MIDI_Typer_Setup.msi` to run the professional Windows installation wizard.
4. (Optional) Check the **"Run at startup"** box during setup to launch MIDI Typer automatically whenever your computer boots up.
5. Look for the custom application icon inside your taskbar system tray area next to the clock!

---

## ⚡ Pro Tip: Lowering Latency (ASIO)

The application handles MIDI note processing instantly, but the legacy built-in Windows sound engine can introduce a slight processing delay. For crisp, professional under-5ms real-time audio response:

1. Download and install a free ASIO audio routing backend like **ASIO4ALL** or **FlexASIO**.
2. Install a free, high-performance font software synthesizer like **CoolSoft VirtualMIDISynth**.
3. Open its settings panel, switch its primary audio device mapping line over to your new **ASIO Driver**, and reduce the sound buffer size slider scale down to **64** or **128 samples**.
4. Launch MIDI Typer—it will automatically detect the low-latency synthesizer channel loop for flawless playability.

---

## 📄 License

This software utility tool is distributed as open-source under the **MIT License**. Feel free to fork, expand layouts, or integrate custom features!

If you have any feedback or feature requests, feel free to open an Issue or reach out via email at **windraman@gmail.com**.
