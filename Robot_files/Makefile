CC = /usr/bin/arm-angstrom-linux-gnueabi-gcc
CFLAGS = -I/usr/include
LDFLAGS = -L/lib -llocoapi -lmotorcomm -lmodbus

all : actuateMotors

# Main function

actuatorMotors: actuateMotors.c
	$(CC) $(CFLAGS) $(LDFLAGS) actuateMotors.c -o actuateMotors
clean:
	rm actuateMotors
