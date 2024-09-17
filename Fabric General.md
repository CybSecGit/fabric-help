
# Piping Into Fabric

## Piping

- Connects output of one command to input of another
- Allows chaining multiple commands for complex operations
- Uses vertical bar symbol "|" between commands
- Enables efficient data processing and manipulation

## Windows
```Powershell
### From Clipboard
 Get-Clipboard | fabric --pattern analyze_claims

### From File
type article.txt | fabric --pattern analyze_claims

### From your your own text
echo "Explain the concept of artificial intelligence" | fabric --pattern ai

### From Youtube Transcript

yt --transcript https://youtube.com/watch?v=uXs-zPc63kM | fabric --stream --pattern extract_wisdom
```
```

## Mac

```
```bash
### From Clipboard
 pbpaste | fabric --pattern analyze_claims

### From File
cat article.txt | fabric --pattern analyze_claims

### From your your own text
echo "Explain the concept of artificial intelligence" | fabric --pattern ai

### From Youtube Transcript
yt --transcript https://youtube.com/watch?v=uXs-zPc63kM | fabric --stream --pattern extract_wisdom
```
