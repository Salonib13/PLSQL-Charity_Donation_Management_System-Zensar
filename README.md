Name : Saloni Shivaji Bhingare.
College Name : Amrutvahini College Of Engineering.
T.E (Computer Engineering)
Roll No. : 82



Project Name: "Charity Donation Management System" 

The system efficiently tracks and manages donors, donations, beneficiaries, and allocation of donations.
Below is a structured explanation:

Key Features
1)Donor Management:
	Register donors with details like name, email, phone, and address.
	Automatically generate unique donor IDs.
2)Donation Management:
	Record donations with details like amount, type (cash, cheque, etc.), and date.
	Link donations to respective donors.
3)Beneficiary Management:
	Add beneficiaries with their needs (e.g., education, health, etc.) and status (e.g., pending, approved).
4)Resource Allocation:
	Allocate donations to beneficiaries with specified amounts.
	Record allocation details like date and allocated amount.
5)Comprehensive Reporting:
	Generate a summary view of all data: donors, donations, beneficiaries, and allocations.
	



Database Components
1)Tables:
	Donors: Stores donor details.
	Donations: Tracks donations linked to donors.
	Beneficiaries: Manages beneficiaries' details and needs.
	Allocation: Records how donations are allocated to beneficiaries.
2)Relationships:
	Donations are linked to donors.
	Allocations link donations and beneficiaries.



System Workflow
1)Donor Registration:
	Add donor details using RegisterDonor.
	Automatically assign IDs with triggers and sequences.
2)Add Donations:
	Record donations using AddDonation.
	Automatically generate donation IDs and link to donors.
3)Add Beneficiaries:
	Register beneficiaries using AddBeneficiary.
	Specify their need type and status.
4)Allocate Donations:
	Assign donations to beneficiaries using AllocateDonation.
	Automatically record allocation details like ID, date, and amount.



Reporting
1)DonorAllocationSummary View:
	Combines data from all tables to show:
	Donor details (name, email, phone).
	Donation details (amount, type, date).
	Beneficiary details (name, need type, status).
	Allocation details (amount, date).

Benefits
1)Centralized management of charity operations.
2)Automated ID generation for consistency and accuracy.
3)Clear traceability of funds from donors to beneficiaries.
4)Simplified reporting for transparency and accountability.




