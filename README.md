PowerMoves Development - ps-realtor (Forked)
A modified version of ps-realtor specifically adapted for the PowerMoves Development Government System and its enhanced property management.

⚠️ IMPORTANT DISCLAIMER & WARNING ⚠️
This repository contains a FORKED and MODIFIED version of the original ps-realtor script. It is designed to work EXCLUSIVELY with the pm-government system developed by PowerMoves Development and its associated ps-housing fork. We strongly advise against using this fork as a standalone replacement for your standard ps-realtor script or integrating it with other non-PowerMoves Development government systems, as it contains specific database and logic changes that may cause incompatibilities or errors.

✨ Key Modifications for pm-government Integration
This fork includes essential changes to support the advanced government and taxation features planned for pm-government, particularly concerning property creation and management. The primary modifications are:

Property Field Management:
Expanded Property Creation: ps-realtor has been modified to allow realtors to define and assign additional critical fields during property creation and listing:

property_type (TEXT): Categorizes properties (e.g., 'residential', 'commercial', 'agricultural', 'industrial'). This is set by the realtor via the ps-realtor interface.

owner_type (TEXT): Categorizes the owning entity ('citizen', 'company', 'government'). This is also set by the realtor via the ps-realtor interface.

is_tax_exempt Support: While ps-realtor's interface does not directly set the is_tax_exempt flag, its database interactions are updated to support this new column. The is_tax_exempt status is ALWAYS set MANUALLY by a Property Assessor via the pm-government tablet, based on roleplay justification. It is NOT automatically set by owner_type or any other factor.

Integration with pm-government System:
The data captured and managed by ps-realtor (specifically property_type and owner_type) is crucial for pm-government's internal property tracking, taxation calculations, and various legislative processes, including determining voter eligibility based on property ownership.

📝 PowerMoves Development Note on Licensing and Attribution
This script is a fork of the original ps-realtor project. All original copyrights, intellectual property, and credits belong to the original authors and contributors of ps-realtor. PowerMoves Development's modifications are layered on top of their foundational work.

We have maintained the original LICENSE file within this repository, which governs the usage and distribution of the original codebase. Our modifications are made in accordance with the terms of that original license.

Original Repository: [PASTE LINK TO THE ORIGINAL ps-realtor GITHUB REPO HERE]

🤝 Contributing & Support
This fork is maintained by PowerMoves Development for its specific use with the pm-government system. While we appreciate interest, we are not actively seeking external contributions for this specific fork unless it's to fix critical bugs or improve pm-government compatibility.

For issues or questions related to this fork's integration with pm-government, please refer to the pm-government repository's issue tracker. For issues with the original, un-modified ps-realtor functionality, please consult the original repository's issue tracker.
# ps-realtor

`/housing` command

# Dependency
1. [ps-housing](https://github.com/Project-Sloth/ps-housing) - go over ps-housing and read the README.
2. [ox_lib](https://github.com/overextended/ox_lib/releases) - Use the latest release. If you do not use the latest release, MAKE SURE TO BUILD THE UI. Find their docs [here](https://overextended.dev/ox_lib#building-the-ui)

# Preview
![image](https://github.com/Project-Sloth/ps-realtor/assets/82112471/24e4018a-cb97-42b0-81df-3b0236c7e2dc)
![image](https://github.com/Project-Sloth/ps-realtor/assets/82112471/4d8ece54-ace1-4ffc-b8fb-90274bc94e72)
![image](https://github.com/Project-Sloth/ps-realtor/assets/82112471/188d259c-4c0f-4c91-905c-bf9b826cc518)
![image](https://github.com/Project-Sloth/ps-realtor/assets/82112471/9e033984-45f2-449d-ba6c-bb8742ac08bd)
![image](https://github.com/Project-Sloth/ps-realtor/assets/82112471/0dd078b8-a941-4316-b9e1-26c696023139)
