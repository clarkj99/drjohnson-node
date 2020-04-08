# DrJohnson Node-Backend

DrJohnson is an Electronic Medical Records application (scaled down). It was written to showcase technologies learned from my Flatiron school coding bootcamp experience, using Nodejsfor model and controller, and React for the views.

## Configuration

## Node Project Creation

```bash
npx express-generator --no-view node
```

## Models

### User (Patient, Provider)

- Email
- Name
- Role

### Profile

- PatientId
- Address
- Photo
- Pharmacy Address
- InsuranceId
- Insurance Type

### History

- PatientId
- …details

### Encounter

- patientId
- providerId
- complaint
- appointment_at
- checkin_at
- …details

### Generators

## Tasks

- [x] Scaffold Node
- [ ] Models and Controllers
- [ ] Authentication and Roles
- [ ] Seed data
- [ ] ICD-10 Lookup/Download
- [ ] Photo for Profile
- [ ] Alexa Skill (?)

## Notes
