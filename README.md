# MyExplorer

# ID: 1512170
# Name: Võ Sơn Hiệp
## email: vosonhiepa@gmail.com
    **Những việc đã làm được**: Hoàn thành File explorer với treeview, list view, splitter, Shell, StatusBar.
    **Main flow**: 
        -Tạo ra TreeView bên trái, ListView bên phải. 
        -Tạo được splitter ở giữa tree view và list view.
        -Dùng Shell ID list để duyệt This PC, ổ đĩa, thư mục, file.
        -Đưa các ổ đĩa thư mục đã duyệt được vào Tree View, List View.
        -Bắt sự kiện window.
        -Tạo được Status Bar và đưa ra dung lượng của một file khi nhấp vào bên phần List view.
        -Bắt được các sự kiện thay đổi của List view, tree view khi tác động vào ổ đĩa/thư mục/tập tin.
    **Additional flow**:
    	-Set được Icon của This PC, Ổ đĩa, File, File exe, Folder từ icon hệ thống
    	-Đổi được icon chuột thành mũi tên 2 chiều khi vào splitter
    	-Thực thi được file bằng ShellExecute

========================================================================
    WIN32 APPLICATION : My_Explorer Project Overview
========================================================================

AppWizard has created this My_Explorer application for you.

This file contains a summary of what you will find in each of the files that
make up your My_Explorer application.


My_Explorer.vcxproj
    This is the main project file for VC++ projects generated using an Application Wizard.
    It contains information about the version of Visual C++ that generated the file, and
    information about the platforms, configurations, and project features selected with the
    Application Wizard.

My_Explorer.vcxproj.filters
    This is the filters file for VC++ projects generated using an Application Wizard. 
    It contains information about the association between the files in your project 
    and the filters. This association is used in the IDE to show grouping of files with
    similar extensions under a specific node (for e.g. ".cpp" files are associated with the
    "Source Files" filter).

My_Explorer.cpp
    This is the main application source file.

/////////////////////////////////////////////////////////////////////////////
AppWizard has created the following resources:

My_Explorer.rc
    This is a listing of all of the Microsoft Windows resources that the
    program uses.  It includes the icons, bitmaps, and cursors that are stored
    in the RES subdirectory.  This file can be directly edited in Microsoft
    Visual C++.

Resource.h
    This is the standard header file, which defines new resource IDs.
    Microsoft Visual C++ reads and updates this file.

My_Explorer.ico
    This is an icon file, which is used as the application's icon (32x32).
    This icon is included by the main resource file My_Explorer.rc.

small.ico
    This is an icon file, which contains a smaller version (16x16)
    of the application's icon. This icon is included by the main resource
    file My_Explorer.rc.

/////////////////////////////////////////////////////////////////////////////
Other standard files:

StdAfx.h, StdAfx.cpp
    These files are used to build a precompiled header (PCH) file
    named My_Explorer.pch and a precompiled types file named StdAfx.obj.

/////////////////////////////////////////////////////////////////////////////
Other notes:

AppWizard uses "TODO:" comments to indicate parts of the source code you
should add to or customize.

/////////////////////////////////////////////////////////////////////////////
