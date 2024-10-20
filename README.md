# Invisible Defender (Mobile)

> Current Version: v2.0.7 | Last APK version: v2.0.6

We completed this project with my university classmate @electricalgorithm in 2021. But now I'm adding it to my github.

This repository made by İstanbul Üniversitesi-Cerrahpaşa Sustainable Energy Research Laboratuary BSc. Students. You must have server files (_invisible defender server_) in order to connect it from the application.

Contributors: @electricalgorithm and @sir-user

![Login Panel](https://github.com/electricalgorithm/invisible-defender/blob/main/assets-GIT/loginPanel.png?raw=true)
![Control Panel](https://github.com/electricalgorithm/invisible-defender/blob/main/assets-GIT/controlPanel.png?raw=true)

### Notes to Ourselves
* Don't install PyCrypto and PyCryptodome at same project. Don't use PyCrypto since its vulnerable.
* PyCryptodomex doesn't have recipe for p4a. Don't use it, either.
* `adb devices` can be used for listing connected Android devices (adb is in your `~/.buildozer` directory.). Also, `adb logcat *:S python:D` can be used for outputs. Don't forget that zsh won't recognize the asteriks, so that put a escape character before it: `adb logcat \*:S python:D`.

### Installing
1. Download the repository.
2. Create a virtual environment with `virtualenv . --python=python3.7`. It should use Python version 3.7.
3. Activate the virtual enviroment.
4. Use pip to install all requirements with `pip install -r requirements.txt`.
5. Now, you can launch the application in your computer with `python main.py` or you can create an -debug- APK with `buildozer -v android debug`. See buildozer for details and further readings.

---

### What to do next? (TR)

- [ ] Kamera aktarımı da şifrelenmeli.
- [ ] `Stop` komutu gittiğinde `Untrusted` hatası veriyor. Düzeltilmesi gerek.

