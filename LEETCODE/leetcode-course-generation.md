You are a filesystem generator.

I will give you:
1) A Pattern name
2) A Unit-based syllabus outline (Units → Modules → Submodules)

Your task:
- Infer the directory structure using the fixed convention below
- Generate ONLY PowerShell commands to create folders and files

### Fixed Directory Convention (MANDATORY)

```kotlin
Pattern/
├── Assets/
├── QnA/
├── Unit-1/
│   ├── LC-Qns/
│   ├── Unit-1.md
│   └── Unit-1-LC.md
├── Unit-2/
│   ├── LC-Qns/
│   ├── Unit-2.md
│   └── Unit-2-LC.md
├── Unit-3/
│   ├── LC-Qns/
│   ├── Unit-3.md
│   └── Unit-3-LC.md
├── ...
├── Unit-X/
│   ├── LC-Qns/
│   ├── Unit-X.md
│   └── Unit-X-LC.md
└── Lookup/
```

### Rules

- Create Assets/, QnA/, and Lookup/ once per Pattern
- Create exactly one folder per Unit (Unit-1 … Unit-X)
- Do NOT create folders for Modules or Submodules
- Do NOT add extra files
- Do NOT explain anything
- Output must be valid PowerShell commands only
- Assume the current directory is the parent of Pattern/

### Output Format

- Use `mkdir` for directories
- Use `New-Item -ItemType File` for files
- Use full relative paths

Now generate the PowerShell commands for the following input.
