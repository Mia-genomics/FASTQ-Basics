# FASTQ-Basics
Learning FASTQ format and quality scores for NGS data analysis
## FASTQ Quality Score Analysis

This project contains three simulated DNA sequencing reads
with different Phred quality scores.

| Read | Phred Score | Error Probability |
|------|-------------|-------------------|
| read_001 | Q40 | 0.01% |
| read_002 | Q20 | 1% |
| read_003 | Q0 | 100% |

## Interpretation

Read 001 has high base quality.
Read 002 has moderate base quality.
Read 003 has extremely low base quality.

Quality control is an important step in NGS analysis
because sequencing errors can affect variant detection.

## Data

The file `example.fastq` contains simulated sequencing reads
created for educational purposes.
