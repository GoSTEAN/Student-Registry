# Implement Student Registry System

## Description

This PR implements the complete Student Registry system. It includes contracts for student management, ownership, and utility functions. The following components are included:

1. **StudentStruct.sol**: Defines the `Student` structure.
2. **Ownable.sol**: Provides ownership management functionality.
3. **StudentCounter.sol**: Manages student ID incrementing.
4. **StudentRegistry.sol**: Main contract for registering, updating, authorizing, and managing students.
5. **MyStudentRegistry.sol**: A wrapper contract for interacting with the `StudentRegistry` contract.
6. **IStudentRegistry.sol**: Interface for the `StudentRegistry` contract.

## How to Test

1. **Deploy Contracts**: Deploy `StudentRegistry` and `MyStudentRegistry` contracts.
2. **Register Student**: Use `MyStudentRegistry` to register a student by sending 1 Ether.
3. **Authorize Student**: Authorize the student using `StudentRegistry`'s `authorizeStudent` method.
4. **Update Student**: Update student details via `MyStudentRegistry`.
5. **Delete Student**: Delete a student's record via `MyStudentRegistry`.

##

 Notes

- Ensure that contract addresses are correctly set during deployment.
- Verify that all function calls are made with the correct parameters and Ether amounts.

---
