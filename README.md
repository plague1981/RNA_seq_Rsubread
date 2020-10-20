# RNA_seq
This project is for analyzing big data generated by NGS sequencing. 

# Rsubread_index_cl.R

=== Prerequisites ===
R Packages:
1. Xmisc
2. Rsubread
=====================
Please see the options by launching help function '-h' or '--help' prior to using this script. 

# Rsubread_align_cl.R
group.xlsx or group.txt
For example.
    Sample_names	      Groups
Sample_names	Groups
A1.S1.gz.subread.BAM             1            0            0            0	A
A2.S2.gz.subread.BAM             1            0            0            0	A
A3.S3.gz.subread.BAM             1            0            0            0	A
B1.S4.gz.subread.BAM             0            1            0            0	B
B2.S5.gz.subread.BAM             0            1            0            0	B
B3.S6.gz.subread.BAM             0            1            0            0	B
C1.S7.gz.subread.BAM             0            0            1            0	C
C2.S8.gz.subread.BAM             0            0            1            0	C
C3.S9.gz.subread.BAM             0            0            1            0	C
D1.S10.gz.subread.BAM            0            0            0            1	D
D2.S11.gz.subread.BAM            0            0            0            1	D
D3.S12.gz.subread.BAM	D
