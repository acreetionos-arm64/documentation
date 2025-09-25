# AcreetionOS ARM64 Port - Project Proposal

**To**: AcreetionOS Maintainers (@Natalie/@LinuxGrandpa)
**From**: John Junkins (@macjunkins)
**Date**: September 2025
**Subject**: Independent ARM64 Port Development

## Project Overview

I'd like to create an ARM64 port of AcreetionOS as an independent side project. This would bring AcreetionOS to modern ARM devices like Raspberry Pi, Pine64 boards, and Arm PCs

## My Approach

**Independent Development**:
- Self-contained project using GitHub infrastructure
- No dependencies on AcreetionOS team resources or timeline
- Complete technical and operational independence

**Hybrid Package Strategy**:
- Use Arch Linux ARM repositories for base system (90% of packages)
- Recreate only AcreetionOS-specific customizations for ARM64
- Minimal maintenance burden while preserving AcreetionOS identity

**Realistic Timeline**:
- Side project with 18-36 month completion window
- No hard deadlines or schedule pressure
- Work progresses as time and interest permit

## What I Need From You (Optional)

**Helpful But Not Required**:
- Access to source code for custom packages (calamares-config, branding, etc.)
- Guidance on what makes AcreetionOS unique vs generic Arch
- Occasional feedback on maintaining AcreetionOS identity

**What I Don't Need**:
- Server resources or infrastructure
- Regular meetings or status updates
- Immediate responses or commitments
- Any ongoing maintenance support

## Benefits to AcreetionOS

**Potential Outcomes**:
- Expands AcreetionOS to ARM64 hardware ecosystem
- Independent validation of distribution architecture
- Possible future collaboration if successful
- No risk or resource commitment from core team

**Relationship**:
- This is a tribute project that respects your work
- Credit and acknowledgments to original AcreetionOS team
- Option to adopt, ignore, or provide feedback as you see fit
- No obligations or expectations on your part
- No confusion about "official" vs independent versions
- Clear distinction as a community-driven port
- No pressure to change your core development philosophy or priorities
- No nagging about project management workflows or development practices
- Just a respectful side project that honors your original vision
- If the community shows interest, you can decide how to proceed
- If not, no harm done
- Full rights and ownership remain with AcreetionOS team
- Full rights to pull in any changes or improvements
- Full rights to discontinue or ignore the ARM64 port at any time

## My Commitment

**What I Promise**:
- Maintain respectful boundaries with your project
- Give proper credit to AcreetionOS origins
- Share results if successful
- No pressure for support or involvement
- Point of contact for questions or clarifications
- Transparent communication if desired
- Point community members to AcreetionOS for official support regarding x86_64 version
- Handle all technical, operational, and community aspects independently

**What I Won't Do**:
- Create confusion about "official" vs independent versions
- Make demands on your time or resources
- Expect ongoing collaboration or maintenance help
- Interfere with your core development work
- Compete with or replace your work
- Pressure you to change your development philosophy or priorities
- Nag you about project management workflows or development practices
- Create any obligations or expectations on your part
- Create any confusion about the relationship between the two projects

**What I am still consider and would like feedback on**:
- Creating a unique Discord server for ARM64 port community
    - Separate from AcreetionOS Discord - I would set up a bot to point users to AcreetionOS Discord for x86_64 support
    - Set up a bot to provide automated build status updates
    - Set up a bot to provide automated announcements of new ARM64 releases
- Setting up a dedicated website or wiki for ARM64 port documentation
- Setting up any kind of social media presence (Twitter, Mastodon, etc)
- Setting up a Patreon or other funding mechanism to cover hosting costs
    - I would not ask for any funding from AcreetionOS team or community and in fact point users to AcreetionOS for any donations or funding before I asked for separate funding for the ARM64 port
- Starting a Rumble channel to post videos about the ARM64 port
    - I am considering this for my own personal channel to post videos about Linux, My commercial applications and teaching other concepts I think are interesting.
**I dislike Social Media and am bad at it**

## Technical Details

**Architecture**: ARM64/aarch64 targeting Raspberry Pi 4/5, Pine64, Arm PCs
**Base System**: Arch Linux ARM repositories
**Custom Packages**: Rebuild AcreetionOS-specific packages for ARM64
**Installer**: Calamares with ARM64 support
**Build System**: archiso with ARM64 adaptations
**Repository**: Independent GitHub repository with full documentation
**Estimated Effort**: 180-250 hours over 18-36 months

## Next Steps

**If Interested**:
- I'd appreciate any guidance on AcreetionOS customizations
- Source access for custom packages would be helpful
- Occasional informal feedback welcome

**If Not Interested**:
- No problem! I'll proceed independently with public information
- Will still give proper credit and acknowledgments
- Door remains open for future collaboration

**Either Way**:
- This project moves forward as an independent effort
- No obligations or expectations on your part
- Your focus remains on the x86_64 version

## Why I'm Doing This

I believe AcreetionOS has a solid foundation that deserves to reach ARM64 users. As someone with time for a long-term side project, I want to contribute to the broader Linux ecosystem while learning distribution development.

This isn't about competing with or replacing your work—it's about extending AcreetionOS's reach to new hardware platforms through independent development. Without any pressure or obligations on your part to change your core development philosophy or priorities. No nagging about project management workflows or devolopment practices. Just a respectful side project that honors your original vision.

## Questions?

Feel free to reach out with questions, concerns, or thoughts. No response needed if you're not interested—I understand you have plenty on your plate with the main distribution.

Thanks for creating AcreetionOS. It's a solid foundation worth building upon.

**Best regards,**
John Junkins
@macjunkins