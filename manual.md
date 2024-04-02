# MarkDown Manual
Nearly all Markdown applications support the basic syntax outlined in the original Markdown design document. There are minor variations and discrepancies between Markdown processors — those are noted inline wherever possible.

- ## Overview
    
    ##### Nearly all Markdown applications support the basic syntax outlined in the original Markdown design document. There are minor variations and discrepancies between Markdown processors — those are noted inline wherever possible.

- ## Headings

    ##### To create a heading, add number signs (#) in front of a word or phrase. The number of number signs you use should correspond to the heading level. 

    *Example 1*
        
        # Heading level 1       
    
    *Result:* 
    # Heading level 1
    
    *Example 2*
    
        #### Heading level 4  

    *Result:*  
    #### Heading level 1

    **Note:** *Markdown applications don’t agree on how to handle a missing space between the number signs (#) and the heading name. For compatibility, always put a space between the number signs and the heading name.*

- ## Paragraphs

    ##### To create paragraphs, use a blank line to separate one or more lines of text.

- ## Lists
    - ### Ordered Lists

    ##### To create an ordered list, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.

    *Example:*
        
        1. First item
        2. Second item
        3. Third item
            1. Indented item
            2. Indented item
        4. Fourth item      
    
    *Result:* 
    1. First item
    2. Second item
    3. Third item
        1. Indented item
        2. Indented item
    4. Fourth item 

     - ### Unordered Lists
    ##### To create an unordered list, add dashes (-), asterisks (*), or plus signs (+) in front of line items. Indent one or more items to create a nested list.

    *Example:*
        
        - First item
        - Second item
        - Third item
            + Indented item
            + Indented item
        - Fourth item      
    
    *Result:* 
    - First item
    - Second item
    - Third item
        + Indented item
        + Indented item
    - Fourth item 

- ## Images

    ##### To add an image, add an exclamation mark (!), followed by alt text in brackets, and the path or URL to the image asset in parentheses. You can optionally add a title in quotation marks after the path or URL.

    *Example 1:*
        
        ![Testing the VEX code for creating liquid tendrils](Tendrils_tool_preview_01-1.jpg)
    
    *Result:* 
    
    ![Testing the VEX code for creating liquid tendrils](Tendrils_tool_preview_01-1.jpg)

    *Example 2:*
        
        [![knitting tool development](andrey-panfilov-knitting-effect-test-10.jpg)](https://cdnb.artstation.com/p/assets/images/images/040/574/337/large/andrey-panfilov-knitting-effewct-test-10.jpg?1629263984)
    
    *Result:* 
   [![knitting tool development](andrey-panfilov-knitting-effect-test-10.jpg)](https://cdnb.artstation.com/p/assets/images/images/040/574/337/large/andrey-panfilov-knitting-effewct-test-10.jpg?1629263984)

- ## links

    ##### To create a link, enclose the link text in brackets (e.g., [Yandex]) and then follow it immediately with the URL in parentheses (e.g., (https://ya.ru)).

    
    *Example 1:*
        
        Alice is cute. I love [Alice](https://alice.yandex.ru). 

    *Result:* 
        
    Alice is cute. I love [Alice](https://alice.yandex.ru).  
