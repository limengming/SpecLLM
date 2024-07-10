# Chapter1
**Typos:**
1. "seperate" (in the description of Amber 25) should be "separate."
2. "Mhz" (in the capability description of Amber 25) should be "MHz."
3. "that" (in the performance comparison of Amber 25 and Amber 23)
should be "than."
4. "has" (in the paragraph about Linux kernel verification) should be
"have."
5. "pipline" (in the last sentence) should be "pipeline."

**Inconsistencies/Contradictions:**
1. The document states that the Amber 23 and Amber 25 cores are 100% software compatible, yet they have differing pipeline stages and cache architectures. This could potentially lead to different performance characteristics not addressed in the compatibility claim.

**Incomplete/Unclear Sections:**
1. The description of the Wishbone interface is vague. More detailed specifications or references to the interface's documentation would improve clarity.
2. The performance metrics (DMIPS per MHz) are provided, but there's no baseline comparison or explanation of what these figures imply in practical terms.
3. The document mentions that the cores have been verified with a 2.4 Linux kernel but does not detail the extent or scope of this verification.
4. The information about the FPGA synthesis is incomplete. Details about the synthesis process, along with any challenges or optimizations, would provide a clearer picture of the implementation process.

# Chapter2
**Typos:**
1. Repetition of "instruction" in sentences (e.g., "the store instruction instruction").
2. Inconsistent capitalization of "Wishbone" in some instances.
3. Use of numerals and words interchangeably (e.g., "three" vs "3" for consistency).
   
**Inconsistencies/Contradictions:**
1. The document describes the pipeline as both a circle and a linear series of stages, which may confuse readers about the actual structure.
2. Some technical descriptions do not align with the provided diagrams, causing potential confusion in understanding the pipeline's operation.
   
**Incomplete/Unclear:**
1. The explanation of how the pipeline handles cache misses is not detailed enough.
2. The description of the ALU's role within the pipeline could be more comprehensive.
3. The impact of pipeline stalls on overall performance is mentioned but not elaborated upon.

# Chapter3
**Typos:**
1. Inconsistent capitalization and punctuation in instruction descriptions (e.g., some start with a capital letter and end with a period, while others do not).
2. Occasional missing spaces between words in the descriptions.
   
**Inconsistencies/Contradictions:**
1. Some instructions have detailed descriptions, while others have very brief or vague descriptions, leading to an uneven understanding of the instruction set.
2. Certain instructions mention flags or modes (e.g., 'p' flag, User mode) without clear explanations, potentially causing confusion.
   
**Incomplete/Unclear:**
1. The document lacks a general introduction or overview of the instruction set's characteristics and its design philosophy.
2. Some instruction descriptions are too brief, lacking in-depth explanation of their operation and use cases.
3. No information on instruction encoding or format is provided, which is critical for understanding how instructions are constructed and processed.

# Chapter4
**Typos:**
1. Inconsistent capitalization in section headings (e.g., "Encode immediate value" vs. "Register transfer offset encoding").
2. Minor punctuation inconsistencies, such as missing periods at the end of some explanatory sentences.
3. Spelling errors in words like "unprivilaged" should be corrected to "unprivileged".

**Inconsistencies/Contradictions:**
1. The document presents certain encoding types in different formats, leading to a lack of uniformity across the section.
2. Some encoding descriptions are not aligned with the stated functionality of the instructions in previous sections.

**Incomplete/Unclear:**
1. Lack of introductory context for the instruction set encoding, which could provide a better understanding of its relevance and application.
2. The descriptions of some encoding types (e.g., "Shift Encoding", "Register transfer offset encoding") are too brief, lacking comprehensive explanation and examples.
3. The section on "Booth's Multiplication Algorithm" could be more detailed, especially in explaining its relevance to the instruction set.

# Chapter5
**Typos:**
1. Inconsistencies in formatting, such as varying indentation and spacing in tables and text.
2. Occasional grammatical errors, like missing articles (e.g., "The" before "processor mode").
3. Spelling errors such as "unprivilaged" instead of "unprivileged".

**Inconsistencies/Contradictions:**
1. Some interrupt types are described with less detail compared to others, creating an imbalance in understanding their functionalities.
2. The document inconsistently refers to processor modes, at times using full names and other times using abbreviations.

**Incomplete/Unclear:**
1. The section lacks a comprehensive introduction explaining the general role and importance of interrupts in the Amber core.
2. Descriptions of certain interrupt types are too brief, lacking sufficient operational details.
3. The relationship between different interrupts and processor modes is mentioned but not adequately explained.

# Chapter6
**Typos:**
1. Inconsistent capitalization in headings and subheadings, such as "Register Sets" vs. "status bits – Part of the PC".
2. Spelling errors, including "unprivilaged" instead of "unprivileged".
3. Some register names are inconsistently formatted (e.g., "r13_svc" vs. "r13 (sp)").

**Inconsistencies/Contradictions:**
1. There's a discrepancy in the representation of register names between tables and text descriptions.
2. The document switches between technical jargon and layman's terms, causing potential confusion.

**Incomplete/Unclear:**
1. Lack of a comprehensive introduction to the register architecture and its significance within the Amber core.
2. Some register descriptions are too brief, lacking details about their specific use and context.
3. No clear explanation of how different register sets are utilized in various processor modes.

# Chapter7
**Typos:**
1. Inconsistent use of spaces in numerical values (e.g., "2 3 4 or 8 ways").
2. The term "Block RAMs" is sometimes capitalized and other times not, needing standardization.

**Inconsistencies/Contradictions:**
1. There is a lack of clarity in the explanation of how the cache size relates to the number of ways, leading to potential confusion.
2. The document fluctuates between technical and less technical language, which might be confusing for the intended audience.

**Incomplete/Unclear:**
1. The section lacks a detailed introduction explaining the role and importance of the cache in the Amber core.
2. There is a need for more detailed explanation of the cache architecture, including how it handles cache misses and its impact on system performance.
3. The relationship between cache configuration and FPGA Block RAMs usage is mentioned but not clearly explained.

# Chapter8
**Typos:**
1. Misspellings such as "modificatiosn" instead of "modifications".
2. Inconsistent formatting in the presentation of Verilog file names (e.g., some in 'code' style format, others not).

**Inconsistencies/Contradictions:**
1. The section mentions different Amber core versions (2x, 23, 25) without clearly differentiating their features or updates.
2. Some files are described with technical details, while others have more general descriptions, leading to inconsistency in the depth of information provided.

**Incomplete/Unclear:**
1. The introduction does not fully explain the overall purpose and scope of the Amber project.
2. Lack of detailed descriptions for some Verilog files, making it difficult to understand their specific functions within the Amber core.
3. The section could benefit from a more explicit explanation of how these Verilog files interact within the Amber core system.
