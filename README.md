SegProso

AUTHOR: Juan María Garrido Almiñana	
VERSION: 2.0 (14/10/2017)

Script to add prosodic segmentation to a TextGrid file.

The script needs as input:
- a wav file with the input utterance
- a TextGrid file

Input TextGrid flies must include two tiers containing:
- orthographic transcription (words) aligned with the signal (tier 1)
- phonetic transcription (SAMPA) aligned with the signal (tier 2)

The script adds to every input TextGrid file	four tiers containing the segmentation into:
- syllables									
- stress groups								
- intonation groups							
- breath groups								

Arguments:
1) wav file		
2) directory of the wav file				
3) TextGrid file			
4) directory of the TextGrid file
5) Output directory				
6) Number of tier containing orthographic transcription in the input TextGrid
7) Number of tier containing phonetic transcription in the input TextGrid
8) Phonetic alphabet (IPA or SAMPA)

Copyright (C) 2012  Juan María Garrido Almiñana                       
                                                                       
This program is free software: you can redistribute it and/or modify 
it under the terms of the GNU General Public License as published by 
the Free Software Foundation, either version 3 of the License, or    
(at your option) any later version.                                  
                                                                     
This program is distributed in the hope that it will be useful,      
but WITHOUT ANY WARRANTY; without even the implied warranty of       
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.                         
                                                                       
See http://www.gnu.org/licenses/ for more details.                   
