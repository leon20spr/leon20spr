```cpp
#include <iostream>
#include <string>
#include <vector>

struct strings {
    std::string name;
    std::string livingCountry;
    std::string languages;
    std::string programmingLanguages;
    std::string interests;
    std::string projects;
    std::string exProjects;
};

int main(void) {
    std::vector<strings> profile(7);

    profile[0].name = "Leon Spreckels";
    profile[0].livingCountry = "Germany";
    profile[0].languages = "german and english";
    profile[0].programmingLanguages = "JavaScript, Python, C++ and C#";
    profile[0].interests = "video-editing, image-editing and music-editing";
    profile[0].projects = "paths-of-blessing.net";
    profile[0].exProjects = "rpg-v.de";

    std::cout << "My name is " + profile[0].name;
    std::cout << ", I live in " + profile[0].livingCountry;
    std::cout << " and speak " + profile[0].languages + ".";
    std::cout << " I program in " + profile[0].programmingLanguages + ".";
    std::cout << " Besides programming, I am interested in " + profile[0].interests + ".";
    std::cout << " My current projects are: " + profile[0].projects + ".";
    std::cout << " My former projects are: " + profile[0].exProjects + ".";
};
```