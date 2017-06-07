http://kernel.org http://mangainn.net http://google.co.uk

http://www.lookingforlyrics.org http://polandhistory.edu http://www.ietf.org

http://www.mitk.org http://developer.arm.com http://eures.eu 

 
Planar Configuration (0028,0006) 
 
The value of Planar Configuration (0028,0006) 
Samples per Pixel (0028,0002) 
Photometric Interpretation (0028,0004) shall be YBR_PARTIAL_420 or MONOCHROME2

Bits Allocated (0028,0100)
Bits Stored (0028,0101) 
High Bit (0028,0102)
Pixel Representation (0028,0103
Rows (0028,0010) shall be either 720 or 1080

Columns (0028,0011) shall be 1280 if Rows is 720, or shall be 1920 if Rows is 1080.

The value of MPEG2 aspect_ratio_information shall be 0011 in the encapsulated MPEG2 data stream corresponding to a 'Display Aspect Ratio' (DAR) of 16:9.

The DICOM attribute Pixel Aspect Ratio (0028,0034) shall be absent. This corresponds to a 'Sampling Aspect Ratio' (SAR) of 1:1.

Cine Rate (0018,0040) and Frame Time (0018,1063) or Frame Time Vector (0018,1065) shall be consistent with the limitations of Main Profile / High Level, as specified in 
