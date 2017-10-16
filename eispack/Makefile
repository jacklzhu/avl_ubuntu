
#FC = f77
FC = gfortran
FLG = -O -fbounds-check -fdefault-real-8 -fdefault-double-8
EISLIB = eispack.a
AR = ar r
RAN = ranlib



eispack.a: eispack.o
	$(FC) -c $(FLG) eispack.f
	$(AR) $(EISLIB) eispack.o
	$(RAN) $(EISLIB)

clean:
	/bin/rm *.o *.a


