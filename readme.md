To run the server open docker and run :

"docker run --rm -it -v D:/Macv_Ai/Media_mtx/mediamtx.yml:/mediamtx.yml:ro -v D:/Macv_Ai/Media_mtx/recordings:/recordings -e MTX_RTSPTRANSPORTS=tcp -p 8554:8554 -p 1935:1935 -p 8888:8888 -p 8889:8889 -p 8890:8890/udp -p 8189:8189/udp -p 9997:9997 bluenviron/mediamtx:latest /mediamtx.yml"