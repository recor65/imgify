# imgify - Convert any file to PNG and back

![Screenshot](/screenshot.png?raw=true "screenshot")

## Install dependencies

Install `libpng`:

- Debian, Ubuntu

	`sudo apt-get install -y libpng-dev`

- CentOS, Fedora, RedHat

	`sudo yum install libpng-devel`

## Get the source and compile

	git clone https://github.com/jweyrich/imgify.git
	cd imgify
	make

## Usage

### bin2png

	usage: bin2png -i <in_filename> -o <out_filename> [-p <pad_byte>]

### png2bin

	usage: png2bin -i <in_filename> -o <out_filename> [-p <pad_byte>]

## License

imgify is distributed under a GPL V2 licence. See the LICENSE file for more information.
