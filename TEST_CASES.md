# Testing Plan – Library Management System

**Author:** Muzammil Ahmed (QA & Documentation Lead)
**Enrollment:** 01-134222-114
**Date:** May 23, 2026

## Test Cases

| ID | Module | Test Description | Expected Result | Priority |
|----|--------|------------------|-----------------|----------|
| TC-01 | Authentication | Login with correct credentials | Redirect to dashboard | High |
| TC-02 | Authentication | Login with wrong password | Error message shown | High |
| TC-03 | Book | Admin adds new book | Book appears in catalog | High |
| TC-04 | Book | Admin edits book | Details updated | Medium |
| TC-05 | Book | Admin deletes book | Book removed | High |
| TC-06 | Search | Search by title | Correct results | Medium |
| TC-07 | Search | Search by author | Correct results | Medium |
| TC-08 | Borrow | Borrow available book | Status = Borrowed | High |
| TC-09 | Borrow | Borrow already borrowed book | "Not available" message | Medium |
| TC-10 | Return | Return book on time | No fine | High |
| TC-11 | Return | Return book late | Fine calculated | High |
| TC-12 | Admin | View all users | User list displayed | Medium |
| TC-13 | Admin | Delete user | User removed | High |

## Bug Reporting Template

Use this template when reporting bugs via GitHub Issues:
