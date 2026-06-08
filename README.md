<div align="center">
  <img width="100%" src="https://raw.githubusercontent.com/17Zoras/17Zoras/main/banner.gif" alt="17Zoras — Drift · Code · ML · DSA · Redline"/>
</div>

<div align="center">
  <br/>
  <img src="https://komarev.com/ghpvc/?username=17Zoras&label=SYSTEM+ACCESS&color=a855f7&style=for-the-badge&labelColor=0c0a1e"/>
  &nbsp;
  <a href="https://github.com/17Zoras?tab=followers">
    <img src="https://img.shields.io/github/followers/17Zoras?label=CREW&style=for-the-badge&color=f59e0b&labelColor=0c0a1e"/>
  </a>
  &nbsp;
  <img src="https://img.shields.io/badge/STATUS-NO_BRAKES_🏁-ef4444?style=for-the-badge&labelColor=0c0a1e"/>
</div>

<br/>

<img width="100%" src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/neon.png"/>

### 🏎️ `driver_profile.cpp`

```cpp
class Zorawar {
public:
    string  name     = "Zorawar Singh";
    string  alias    = "17Zoras";
    string  ride     = "BMW M3 E46 — Touge Spec";
    string  location = "India 🇮🇳";
    string  culture  = "Sikh 🔱 | Focused | Driven";

    vector<string> roles = {
        "ML Engineer",
        "Full-Stack Dev",
        "DSA Racer (C++)"
    };

    vector<string> languages = {
        "Python", "C++", "Java",
        "JavaScript", "HTML", "CSS"
    };

    vector<string> focus = {
        "Machine Learning",
        "Computer Vision",
        "Data Structures & Algorithms"
    };

    string building = "Turning pixels into apps that hit the redline.";
    string motto    = "No brakes on the downhill.";
    string fun_fact = "Debugging at midnight, fueled by coffee and momentum ☕";

    void say_hi() {
        cout << "Welcome to the touge. Let's race some code. 🏁" << endl;
    }
};

int main() {
    Zorawar me;
    me.say_hi();
    return 0;
}
