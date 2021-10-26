# ziher_mono

## windows

Symlink ziher_mono/ziher/F18 <- ziher_mono/F18

    REM run as administrator:
    mklink /D  %USERPROFILE%\dev\ziher_mono\ziher\src\F18 %USERPROFILE%\dev\ziher_mono\F18 

    %USERPROFILE%\dev\ziher_mono\ziher\src> bazel-x86 build //F18:F18.dll  --//bazel:windows_build=x86


## bazel query

<pre>
C:\Users\ernad.husremovic.SA\dev\ziher_mono\ziher\src>bazel-x86 query //...
//zh_xlsxwriter:zh_xlsxwriter_zh_c
//zh_xlsxwriter:zh_xlsxwriter_zh
//zh_xlsxwriter:zh_xlsxwriter
//zh_xlsxwriter:headers
//zh_xlsxwriter:c_sources
//zh_tools:zh_tools_zh_c
//zh_tools:zh_tools_zh
//zh_tools:zh_tools
//zh_tools:headers_filegroup
//zh_tools:headers
//zh_tools:c_sources
//zh_tcp_ip:zh_tcp_ip_zh_c
//zh_tcp_ip:zh_tcp_ip_zh
//zh_tcp_ip:zh_tcp_ip
//zh_tcp_ip:headers_filegroup
//zh_tcp_ip:headers
//zh_tcp_ip:c_sources
//zh_ssl:zh_ssl_zh_c
//zh_ssl:zh_ssl_zh
//zh_ssl:zh_ssl
//zh_ssl:headers_filegroup
//zh_rtl/gt:headers_filegroup
//zh_pgsql:zh_pgsql_zh_c
//zh_pgsql:zh_pgsql_zh
//zh_pgsql:zh_pgsql
//zh_pgsql:headers_filegroup
//zh_pgsql:headers
//zh_pgsql:c_sources
//zh_minizip:zh_minizip_zh_c
//zh_minizip:zh_minizip_zh
//zh_minizip:zh_minizip
//zh_minizip:headers_filegroup
//zh_minizip:headers
//zh_minizip:c_sources
//zh_harupdf:zh_harupdf_zh_c
//zh_harupdf:zh_harupdf_zh
//zh_harupdf:zh_harupdf
//zh_harupdf:headers_filegroup
//zh_harupdf:headers
//zh_harupdf:c_sources
//zh_debug:zh_debug_zh_c
//zh_debug:zh_debug_zh
//zh_debug:zh_debug
//third_party/xlsxwriter:xlsxwriter
//third_party/xlsxwriter:headers
//third_party/xlsxwriter:c_sources
//third_party/png:headers
//third_party/png:c_sources
//third_party/minizip:minizip
//third_party/minizip:headers
//third_party/minizip:c_sources
//third_party/libpq:libpq
//third_party/libpq:headers
//third_party/libpq:c_sources
//third_party/harupdf:headers
//third_party/harupdf:harupdf
//third_party/png:png
//third_party/harupdf:c_sources
//test:run_hello_dbf_win
//test:hello_world
//test:hello_world_zh_lib_c
//test:hello_world_zh_lib
//test:hello_threads
//test:hello_threads_zh_lib_c
//test:hello_threads_zh_lib
//zh_vm:headers_filegroup
//test:hello_dbf_zh_lib_c
//test:hello_dbf
//test:hello_dbf_dll_import
//test:hello_dbf_import_lib
//test:hello_dbf.dll
//test:ziher
//test:ziher_dll_import
//test:ziher_import_lib
//test:ziher.dll
//zh_zero:headers
//zh_zero:c_sources
//zh_vm:headers
//zh_vm:c_sources
//zh_rtl/rdd:c_sources
//zh_rtl/gt:headers
//zh_rtl/gt:c_sources
//zh_rtl:c_sources
//zh_macro:headers
//zh_macro:c_sources
//zh_comp:headers
//third_party/zlib:headers
//third_party/zlib:c_sources
//third_party/pcre2:c_sources
//test:hello_dbf_zh_lib
//test:hello_codepage
//test:hello_codepage_zh_lib_c
//test:hello_codepage_zh_lib
//test:hello_code_block
//zh_vm:zh_vm_zh_c
//zh_vm:zh_vm_zh
//zh_rtl/rdd:zh_rtl_rdd_zh_c
//zh_rtl/rdd:zh_rtl_rdd_zh
//zh_rtl/rdd:zh_rtl_rdd
//zh_rtl/rdd:headers
//zh_rtl/gt:zh_rtl_gt_zh_c
//zh_rtl/gt:zh_rtl_gt_zh
//zh_rtl/gt:zh_rtl_gt
//zh_rtl:zh_rtl_zh_c
//zh_rtl:zh_rtl_zh
//zh_macro:zh_macro
//zh_macro:zh_macro_y
//test:hello_code_block_zh_lib_c
//zh_rtl:zh_rtl
//zh_vm:zh_vm
//zh_rtl:headers
//third_party/zlib:zlib
//third_party/pcre2:pcre2
//third_party/pcre2:headers
//test:hello_code_block_zh_lib
//zh_rtl:headers_filegroup
//zh_comp/main:zhcomp
//zh_pp:pp_table
//zh_zero:headers_filegroup
//zh_pp/main:zhpp
//zh_pp:zh_pp
//zh_comp:zh_comp
//zh_zero:zh_zero
//zh_comp:zh_comp_y
//java/jodreports/src/main/java/org/jodreports/cli:jodreports-cli
//java/jodreports:jodreports
//F18/include:headers_filegroup
//F18/include:headers
//bazel:windows
//bazel:windows_x86
//bazel:windows_x64
//bazel:windows_build
Loading: 31 packages loaded
</pre>


F18:

<pre>
bazel-x86 query //F18/...
//F18/include:headers
//F18:ziher
//F18:F18-klijent-lib_import
//F18:F18-klijent-lib.so
//F18:F18-klijent
//F18:F18_import
//F18:F18.so
//F18:ziher_import
//F18:ziher.so
//F18:F18
//F18:F18_dll_import
//F18:F18_import_lib
//F18:F18.dll
//F18:ziher_dll_import
//F18:ziher_import_lib
//F18:ziher.dll
//F18:F18_zh
//F18/include:headers_filegroup
//F18:fin_headers_filegroup
</pre>