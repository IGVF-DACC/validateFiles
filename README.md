# validateFiles

This tool is developed by Jim Kent from UCSC Genome Bioinformatics Group and downloaded here:
<http://hgdownload.cse.ucsc.edu/admin/exe/linux.x86_64/>

It validates the format of different genomic files. Exits with a zero status for no errors detected and non-zero for errors. Uses filename 'stdin' to read from stdin. Automatically decompresses Files in .gz, .bz2, .zip, .Z format. Accepts multiple input files of the same type.Writes Error messages to stderr.

It is used for IGVF project to validate those file formats: bed, bigWig, bigInteract, bigBed, bedGraph and bedpe.

The version number is 442.
