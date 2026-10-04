# Chess Game Reconstruction & Transcript Corrections

A small Python portfolio project demonstrating chess game reconstruction,
move validation, transcript error detection, and expert-assisted correction.

## Motivation

AI training and chess-data projects may require human experts to reconstruct
games, validate move sequences, identify transcript errors, and correct
inconsistent chess data.

This project demonstrates a simple workflow combining competitive chess
expertise with Python-based validation.

## Test Game

Peter Leko vs. Arjun Erigaisi  
46th Chess Olympiad 2026, Samarkand  
Ruy Lopez, Classical (Cordel) Defence

## Workflow

Chess transcript
→ Move reconstruction
→ Python validation
→ Error detection
→ Expert review
→ Verified correction
→ Re-validation

## Tests

### Test 1 — Valid Move Sequence
Validates a correctly reconstructed sequence from the game.

### Test 2 — Transcript Error Detection
Introduces an intentional transcription error (`6...Bg5`) and detects
that the move is inconsistent with the current board position.

### Test 3 — Expert-Assisted Transcript Correction
The detected error is reviewed and corrected to the verified move
`6...Bg4`, after which the sequence is successfully revalidated.

## Tools

- Python
- python-chess
- Google Colab

## Skills Demonstrated

- Chess game reconstruction
- Standard Algebraic Notation (SAN)
- Chess transcript QA
- Move legality validation
- Error detection
- Expert-assisted correction
- Python
- Attention to detail

## Author

Ahmad Harba  
FIDE-rated competitive chess player  
Classical: 1903 | Rapid: 1903 | Blitz: 1953
