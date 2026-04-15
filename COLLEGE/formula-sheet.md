Give formulas in **Obsidian-ready LaTeX math blocks using $$ ... $$ only**.

For each item:

1. Start with a **clear heading (no ##, just plain Markdown heading)**
    
2. Write the **formula in a LaTeX block** with:
    
    - `\Huge` formatting
        
    - Clean notation using `\left( \right)`
        
    - No `align` environment unless necessary
        
3. Immediately below, provide **symbol definitions in a separate LaTeX block** using:
    
    - `\begin{aligned}`
        
    - One symbol per line
        
    - Format: `symbol &: meaning`
        

Structure:

Heading

$$  
\Huge  
formula  
$$

$$  
\Huge  
\begin{aligned}  
symbol &: meaning \  
symbol &: meaning  
\end{aligned}  
$$

Rules:

- Do NOT use bullet points
    
- Do NOT write definitions in plain text
    
- Do NOT use inline explanations
    
- Keep everything in LaTeX blocks
    
- Keep notation clean and consistent
    
- Use only symbols present in the formula