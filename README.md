# MyFFmpeg
汇集了ffmpeg源码和编译版本，方便取用，其中编译了ffplay，修改了源码使https-flv支持h.265

qt中接入ffmpeg库，在pro文件中
FFMPEG_HOME = $$PWD/ffmpeg/ffmpeg-5.1.3-265
INCLUDEPATH += $${FFMPEG_HOME}/include
LIBS += -L$${FFMPEG_HOME}/lib \
   -lavcodec \
   -lavdevice \
   -lavfilter \
   -lavformat \
   -lavutil \
   -lswscale \
   -lswresample