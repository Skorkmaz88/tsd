# tsd

emih@semih-OMEN-by-HP-Laptop-17-an0xx:~/Downloads/code_pt/arty/build$ make
[ 11%] Building CXX object src/CMakeFiles/arty.dir/main.cpp.o
/home/semih/Downloads/code_pt/arty/src/main.cpp: In function ‘int main(int, char**)’:
/home/semih/Downloads/code_pt/arty/src/main.cpp:249:89: error: no matching function for call to ‘min(size_t&, int&)’
 e_t y = std::max(0, debug_ymin), h = std::min(img.height, debug_ymax); y < h; y++) {
   https://docs.google.com/document/d/1mr4IoH4oIGQlYSzu1C3YUPW0VmgcmRn45r4CU2yk4Rw/edit?usp=sharing                                                                  ^
In file included from /usr/include/c++/7/bits/char_traits.h:39:0,
                 from /usr/include/c++/7/ios:40,
                 from /usr/include/c++/7/ostream:38,
                 from /usr/include/c++/7/iostream:39,
                 from /home/semih/Downloads/code_pt/arty/src/main.cpp:1:
/usr/include/c++/7/bits/stl_algobase.h:195:5: note: candidate: template<class _Tp> const _Tp& std::min(const _Tp&, const _Tp&)
     min(const _Tp& __a, const _Tp& __b)
     ^~~
/usr/include/c++/7/bits/stl_algobase.h:195:5: note:   template argument deduction/substitution failed:
/home/semih/Downloads/code_pt/arty/src/main.cpp:249:89: note:   deduced conflicting types for parameter ‘const _Tp’ (‘long unsigned int’ and ‘int’)
 e_t y = std::max(0, debug_ymin), h = std::min(img.height, debug_ymax); y < h; y++) {
                                                                     ^
In file included from /usr/include/c++/7/bits/char_traits.h:39:0,
                 from /usr/include/c++/7/ios:40,
                 from /usr/include/c++/7/ostream:38,
                 from /usr/include/c++/7/iostream:39,
                 from /home/semih/Downloads/code_pt/arty/src/main.cpp:1:
/usr/include/c++/7/bits/stl_algobase.h:243:5: note: candidate: template<class _Tp, class _Compare> const _Tp& std::min(const _Tp&, const _Tp&, _Compare)
     min(const _Tp& __a, const _Tp& __b, _Compare __comp)
     ^~~
/usr/include/c++/7/bits/stl_algobase.h:243:5: note:   template argument deduction/substitution failed:
/home/semih/Downloads/code_pt/arty/src/main.cpp:249:89: note:   deduced conflicting types for parameter ‘const _Tp’ (‘long unsigned int’ and ‘int’)
 e_t y = std::max(0, debug_ymin), h = std::min(img.height, debug_ymax); y < h; y++) {
                                                                     ^
In file included from /usr/include/c++/7/algorithm:62:0,
                 from /home/semih/Downloads/code_pt/arty/src/random.h:7,
                 from /home/semih/Downloads/code_pt/arty/src/samplers.h:8,
                 from /home/semih/Downloads/code_pt/arty/src/lights.h:6,
                 from /home/semih/Downloads/code_pt/arty/src/scene.h:8,
                 from /home/semih/Downloads/code_pt/arty/src/main.cpp:10:
/usr/include/c++/7/bits/stl_algo.h:3450:5: note: candidate: template<class _Tp> _Tp std::min(std::initializer_list<_Tp>)
     min(initializer_list<_Tp> __l)
     ^~~
/usr/include/c++/7/bits/stl_algo.h:3450:5: note:   template argument deduction/substitution failed:
/home/semih/Downloads/code_pt/arty/src/main.cpp:249:89: note:   mismatched types ‘std::initializer_list<_Tp>’ and ‘long unsigned int’
 e_t y = std::max(0, debug_ymin), h = std::min(img.height, debug_ymax); y < h; y++) {
                                                                     ^
In file included from /usr/include/c++/7/algorithm:62:0,
                 from /home/semih/Downloads/code_pt/arty/src/random.h:7,
                 from /home/semih/Downloads/code_pt/arty/src/samplers.h:8,
                 from /home/semih/Downloads/code_pt/arty/src/lights.h:6,
                 from /home/semih/Downloads/code_pt/arty/src/scene.h:8,
                 from /home/semih/Downloads/code_pt/arty/src/main.cpp:10:
/usr/include/c++/7/bits/stl_algo.h:3456:5: note: candidate: template<class _Tp, class _Compare> _Tp std::min(std::initializer_list<_Tp>, _Compare)
     min(initializer_list<_Tp> __l, _Compare __comp)
     ^~~
/usr/include/c++/7/bits/stl_algo.h:3456:5: note:   template argument deduction/substitution failed:
/home/semih/Downloads/code_pt/arty/src/main.cpp:249:89: note:   mismatched types ‘std::initializer_list<_Tp>’ and ‘long unsigned int’
 e_t y = std::max(0, debug_ymin), h = std::min(img.height, debug_ymax); y < h; y++) {
                                                                     ^
/home/semih/Downloads/code_pt/arty/src/main.cpp:251:92: error: no matching function for call to ‘min(size_t&, int&)’
 ze_t x = std::max(0, debug_xmin), w = std::min(img.width, debug_xmax); x < w; x++) {
                                                                     ^
In file included from /usr/include/c++/7/bits/char_traits.h:39:0,
                 from /usr/include/c++/7/ios:40,
                 from /usr/include/c++/7/ostream:38,
                 from /usr/include/c++/7/iostream:39,
                 from /home/semih/Downloads/code_pt/arty/src/main.cpp:1:
/usr/include/c++/7/bits/stl_algobase.h:195:5: note: candidate: template<class _Tp> const _Tp& std::min(const _Tp&, const _Tp&)
     min(const _Tp& __a, const _Tp& __b)
     ^~~
/usr/include/c++/7/bits/stl_algobase.h:195:5: note:   template argument deduction/substitution failed:
/home/semih/Downloads/code_pt/arty/src/main.cpp:251:92: note:   deduced conflicting types for parameter ‘const _Tp’ (‘long unsigned int’ and ‘int’)
 ze_t x = std::max(0, debug_xmin), w = std::min(img.width, debug_xmax); x < w; x++) {
                                                                     ^
In file included from /usr/include/c++/7/bits/char_traits.h:39:0,
                 from /usr/include/c++/7/ios:40,
                 from /usr/include/c++/7/ostream:38,
                 from /usr/include/c++/7/iostream:39,
                 from /home/semih/Downloads/code_pt/arty/src/main.cpp:1:
/usr/include/c++/7/bits/stl_algobase.h:243:5: note: candidate: template<class _Tp, class _Compare> const _Tp& std::min(const _Tp&, const _Tp&, _Compare)
     min(const _Tp& __a, const _Tp& __b, _Compare __comp)
     ^~~
/usr/include/c++/7/bits/stl_algobase.h:243:5: note:   template argument deduction/substitution failed:
/home/semih/Downloads/code_pt/arty/src/main.cpp:251:92: note:   deduced conflicting types for parameter ‘const _Tp’ (‘long unsigned int’ and ‘int’)
 ze_t x = std::max(0, debug_xmin), w = std::min(img.width, debug_xmax); x < w; x++) {
                                                                     ^
In file included from /usr/include/c++/7/algorithm:62:0,
                 from /home/semih/Downloads/code_pt/arty/src/random.h:7,
                 from /home/semih/Downloads/code_pt/arty/src/samplers.h:8,
                 from /home/semih/Downloads/code_pt/arty/src/lights.h:6,
                 from /home/semih/Downloads/code_pt/arty/src/scene.h:8,
                 from /home/semih/Downloads/code_pt/arty/src/main.cpp:10:
/usr/include/c++/7/bits/stl_algo.h:3450:5: note: candidate: template<class _Tp> _Tp std::min(std::initializer_list<_Tp>)
     min(initializer_list<_Tp> __l)
     ^~~
/usr/include/c++/7/bits/stl_algo.h:3450:5: note:   template argument deduction/substitution failed:
/home/semih/Downloads/code_pt/arty/src/main.cpp:251:92: note:   mismatched types ‘std::initializer_list<_Tp>’ and ‘long unsigned int’
 ze_t x = std::max(0, debug_xmin), w = std::min(img.width, debug_xmax); x < w; x++) {
                                                                     ^
In file included from /usr/include/c++/7/algorithm:62:0,
                 from /home/semih/Downloads/code_pt/arty/src/random.h:7,
                 from /home/semih/Downloads/code_pt/arty/src/samplers.h:8,
                 from /home/semih/Downloads/code_pt/arty/src/lights.h:6,
                 from /home/semih/Downloads/code_pt/arty/src/scene.h:8,
                 from /home/semih/Downloads/code_pt/arty/src/main.cpp:10:
/usr/include/c++/7/bits/stl_algo.h:3456:5: note: candidate: template<class _Tp, class _Compare> _Tp std::min(std::initializer_list<_Tp>, _Compare)
     min(initializer_list<_Tp> __l, _Compare __comp)
     ^~~
/usr/include/c++/7/bits/stl_algo.h:3456:5: note:   template argument deduction/substitution failed:
/home/semih/Downloads/code_pt/arty/src/main.cpp:251:92: note:   mismatched types ‘std::initializer_list<_Tp>’ and ‘long unsigned int’
 ze_t x = std::max(0, debug_xmin), w = std::min(img.width, debug_xmax); x < w; x++) {
                                                                     ^
src/CMakeFiles/arty.dir/build.make:62: recipe for target 'src/CMakeFiles/arty.dir/main.cpp.o' failed
make[2]: *** [src/CMakeFiles/arty.dir/main.cpp.o] Error 1
CMakeFiles/Makefile2:85: recipe for target 'src/CMakeFiles/arty.dir/all' failed
make[1]: *** [src/CMakeFiles/arty.dir/all] Error 2
Makefile:83: recipe for target 'all' failed
make: *** [all] Error 2
