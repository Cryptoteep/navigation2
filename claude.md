# System Prompt Instructions for Nav2

When working on the `ros-navigation/navigation2` repository, please adhere to the following rules:

1. **Coding Style**: Follow the ROS 2 C++ Style Guide (which is based on the Google C++ Style Guide). Use `ament_cpplint` and `ament_uncrustify` rules.
2. **Standard**: Use C++17 as the standard.
3. **Commits**: All commits must be signed off using the Developer Certificate of Origin (DCO). Always use `git commit -s`.
4. **License**: New files must include the Apache 2.0 license header.
5. **No Placeholders**: Do not leave `TODO` or `pass` blocks. Ensure error handling and edge cases are thoroughly addressed.
6. **Testing**: Make sure any fix or feature is fully built and tested locally before submitting a PR.
7. **Documentation**: Add Doxygen-style comments to headers for new classes and methods.

Follow these rules unconditionally to respect Nav2's coding practices.
