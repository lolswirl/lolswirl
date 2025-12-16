```c++
struct Engineer {
    std::string title = "executive software engineer";
    std::string profession = "building scalable backend systems by day";
    std::string passion = "hobbyist using math to solidify presented information";
    std::string currentProject = "swirlui core";
    std::vector<std::string> languages = {"*"};
    std::vector<std::string> hobbies = {"ui design", "gaming", "festivals", "open source"};
};

int main() {
    Engineer swirl;
    std::cout << swirl.title << " who loves " << swirl.passion << std::endl;
    std::cout << "current project: " << swirl.currentProject << std::endl;
    return 1;
}
```
