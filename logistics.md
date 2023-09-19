---
layout: page
title: Course Logistics
permalink: /logistics/
---
## Contact
Please contact us by reaching directly on the staff email IDs with any questions, or by
making a private post on ED for registered students. Individual appointments outside OH can be made by directly contacting
the respective staff.

## Course Staff
- **Pulkit Tandon**
  - Research Engineer at [Granica](https://granica.ai)
  - tpulkit [AT] stanford [DOT] edu
  - **Office hours:** `Wednesdays 6pm-7pm, Shriram 104`
- **Shubham Chandak** 
    - Applied Scientist at Amazon Web Services
    - schandak [AT] stanford [DOT] edu
    - **Office hours:** `TBD`
- **Prof. Tsachy Weissman** 
    - Electrical Engineering, Stanford
    - tsachy [AT] stanford [DOT] edu
    - **Office hours:** `TBD`
- **Noah Huffman**
  - Physics, Stanford
  - nhuffman [AT] stanford [DOT] edu
  - **Office hours:** `TBD`


## Lectures
- [Link to explore courses](https://explorecourses.stanford.edu/search?view=catalog&filter-coursestatus-Active=on&page=0&catalog=&academicYear=&q=EE274&collapse=)
- **Date & Time:** Biweekly in-person lectures `Mon, Wed 4:30 PM - 5:50 PM`
- **Location**: [Shriram 104](https://campus-map.stanford.edu/?srch=Shriram+104)


## Course elements and grading (tentative)
EE 274 is a `3 unit` course - auditing allowed with instructor permission. The graded course elements include:

- `4` assignments with both theoretical and programming components (`15%` each)
- Short quizzes after every lecture, due before next (`10%`)
- final project (`30%`)
- [bonus] participation in the course (`5%`)

## Useful Links
- [Stanford Compression Library](https://github.com/kedartatwawadi/stanford_compression_library) (a collection of compression algorithms implemented in Python)
- [Lecture Notes](https://stanforddatacompressionclass.github.io/notes/contents.html) (for the course notes)
- ED: available via [Canvas](https://canvas.stanford.edu) (for course Q&A, discussions and announcements)
- Gradescope: available via [Canvas](https://canvas.stanford.edu) (for quizzes and assignment submissions)
- Panopto: available via [Canvas](https://canvas.stanford.edu) (for the course lectures video recordings)
- [IT Forum](https://web.stanford.edu/group/it-forum/talks/) (for talks on various topics related to compression)

## Prerequisites
Basic probability and programming background (EE178, CS106B or equivalent), or instructor’s permission. Background in statistical signal processing (EE278) and in information theory (EE276) may be helpful for appreciating some of the material, but is not assumed and the relevant background will be covered in class. Some of the final projects will be tailored to the students' backgrounds. 

## Textbook
There is no required textbook, lecture notes and slides will be provided as relevant. 
We might provide references to textbooks from time to time for additional reading.

---

## Course Outline (tentative)
**Lossless Compression Basics**
- Introduction to data compression, prefix-free codes
- Construction of generic prefix-free codes, Kraft Inequality
- Information theory basics, fundamental limits on compression
- Huffman coding, practical prefix-free codes
- Arithmetic coding, adaptive arithmetic coding
- Asymmetric Numeral Systems, rANS/tANS compressors

**Universal lossless compression**
- Asymptotic Equipartition theory
- Non-iid data compression, Entropy rate, context-based Arithmetic coder
- Universal lossless compression, Lempel-Ziv (LZ) 77/78 schemes
- Case Study: `GZIP`, how to implement LZ-based schemes in practice

**Lossy Compression fundamentals**
- Introduction to Lossy compression, scalar-quantization
- Rate-Distortion theory, intuition + practical limitations
- Transform coding, Case Study: Speech compression

**Image/Video Compression**
- Case Study: Image compression `JPEG, BPG`
- Machine Learning based image compression
- Video compression, `H264, H265` video standards
- Perceptual Quality metrics for image/video compression

**Special Topics**

Based on interest and time. Some of these topics will be covered through invited IT Forum talks and also available as
an option for the final projects.
- Succinct data structures, compression of data structures in the RAM
- Burrows-Wheeler transform
- Lossy compression and de-noising
- Distributed compression, practical applications
- Compression of neural network models







