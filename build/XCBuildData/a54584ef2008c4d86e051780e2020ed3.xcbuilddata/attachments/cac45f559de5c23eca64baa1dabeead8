#!/bin/sh
set -e
if test "$CONFIGURATION" = "Debug"; then :
  cd "/Users/benbromley/University/UoD/Modules/02 - Audio Software Engineering/Programming/ALL_SDK/projects/03_Lab_StereoWidth/mac_build/project_source/cmake/vst_cmake"
  codesign --force --verbose --sign - /Users/benbromley/University/UoD/Modules/02\ -\ Audio\ Software\ Engineering/Programming/ALL_SDK/projects/03_Lab_StereoWidth/mac_build/VST3/Debug/03_Lab_StereoWidth_VST.vst3
  cd "/Users/benbromley/University/UoD/Modules/02 - Audio Software Engineering/Programming/ALL_SDK/projects/03_Lab_StereoWidth/mac_build/bin"
  /opt/homebrew/bin/cmake -E echo [SMTG] Validator started...
  "/Users/benbromley/University/UoD/Modules/02 - Audio Software Engineering/Programming/ALL_SDK/projects/03_Lab_StereoWidth/mac_build/bin/Debug/validator" /Users/benbromley/University/UoD/Modules/02\ -\ Audio\ Software\ Engineering/Programming/ALL_SDK/projects/03_Lab_StereoWidth/mac_build/VST3/Debug/03_Lab_StereoWidth_VST.vst3 
  /opt/homebrew/bin/cmake -E echo [SMTG] Validator finished.
  cd "/Users/benbromley/University/UoD/Modules/02 - Audio Software Engineering/Programming/ALL_SDK/projects/03_Lab_StereoWidth/mac_build/project_source/cmake/vst_cmake"
  /opt/homebrew/bin/cmake -E make_directory /Users/benbromley/Library/Audio/Plug-Ins/VST3
  ln -svfF /Users/benbromley/University/UoD/Modules/02\ -\ Audio\ Software\ Engineering/Programming/ALL_SDK/projects/03_Lab_StereoWidth/mac_build/VST3/Debug/03_Lab_StereoWidth_VST.vst3 /Users/benbromley/Library/Audio/Plug-Ins/VST3/03_Lab_StereoWidth_VST.vst3
fi
if test "$CONFIGURATION" = "Release"; then :
  cd "/Users/benbromley/University/UoD/Modules/02 - Audio Software Engineering/Programming/ALL_SDK/projects/03_Lab_StereoWidth/mac_build/project_source/cmake/vst_cmake"
  codesign --force --verbose --sign - /Users/benbromley/University/UoD/Modules/02\ -\ Audio\ Software\ Engineering/Programming/ALL_SDK/projects/03_Lab_StereoWidth/mac_build/VST3/Release/03_Lab_StereoWidth_VST.vst3
  cd "/Users/benbromley/University/UoD/Modules/02 - Audio Software Engineering/Programming/ALL_SDK/projects/03_Lab_StereoWidth/mac_build/bin"
  /opt/homebrew/bin/cmake -E echo [SMTG] Validator started...
  "/Users/benbromley/University/UoD/Modules/02 - Audio Software Engineering/Programming/ALL_SDK/projects/03_Lab_StereoWidth/mac_build/bin/Release/validator"  /Users/benbromley/University/UoD/Modules/02\ -\ Audio\ Software\ Engineering/Programming/ALL_SDK/projects/03_Lab_StereoWidth/mac_build/VST3/Release/03_Lab_StereoWidth_VST.vst3
  /opt/homebrew/bin/cmake -E echo [SMTG] Validator finished.
  cd "/Users/benbromley/University/UoD/Modules/02 - Audio Software Engineering/Programming/ALL_SDK/projects/03_Lab_StereoWidth/mac_build/project_source/cmake/vst_cmake"
  /opt/homebrew/bin/cmake -E make_directory /Users/benbromley/Library/Audio/Plug-Ins/VST3
  ln -svfF /Users/benbromley/University/UoD/Modules/02\ -\ Audio\ Software\ Engineering/Programming/ALL_SDK/projects/03_Lab_StereoWidth/mac_build/VST3/Release/03_Lab_StereoWidth_VST.vst3 /Users/benbromley/Library/Audio/Plug-Ins/VST3/03_Lab_StereoWidth_VST.vst3
fi

