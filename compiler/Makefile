all: v vc

v: vc
	./vc -o v .

vc: v.c
	cc -std=c11 -w -o vc v.c

v.c:
	wget https://vlang.io/v.c

clean:
	-rm v vc v.c
