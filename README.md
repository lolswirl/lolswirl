```c++
struct Engineer {
    std::string title = "executive software engineer";
    std::string profession = "building scalable backend systems by day";
    std::string passion = "crafting wow addons by night";
    std::string currentProject = "swirlui core";
    std::vector<std::string> languages = {"c++", "python", "java", "javascript", "lua"};
    std::vector<std::string> hobbies = {"ui design", "gaming", "open source"};
};

int main() {
    Engineer swirl;
    std::cout << swirl.title << " who loves " << swirl.passion << std::endl;
    std::cout << "current project: " << swirl.currentProject << std::endl;
    return 1;
}
```
