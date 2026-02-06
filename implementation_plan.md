# Implementation Plan - Add CIDR Section

The user identified that CIDR (Classless Inter-Domain Routing) is mentioned but not widely explained in the networking course. I will add a dedicated section to address this.

## User Review Required
> [!NOTE]
> This is a content addition to a Markdown course file. No code changes are involved.

## Proposed Changes

### Network Fundamentals Course

#### [MODIFY] [networking_course.md](file:///c:/dev/work/network-fundamentals-course/networking_course.md)
- Insert a new section `1.2.1 The Modern Way: CIDR` after the table of IP Classes in Section 1.2.
- The section will explain:
    - What CIDR stands for.
    - The limitations of Classful addressing (waste).
    - The `/xx` suffix notation.
    - How it allows variable-length subnet masking (VLSM).

## Verification Plan

### Manual Verification
- Review the rendered markdown to ensure the new section fits logically between "IPv4 Addressing" and "Subnet Masks".
- Check that the transition from Classes to CIDR makes sense.
