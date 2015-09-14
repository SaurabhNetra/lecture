.PHONY: submit clean

submit: centroid
#	qsub centroid.pbs

centroid: centroid.c centroid.h centroid_timer.c
	/usr/local/bin/gcc-5 -o centroid centroid.c centroid_timer.c -fopenmp

clean:
	rm -f centroid
	rm *.o*
