report_id: str - uuid
user_id: str - uuid
license: str
	- "RN - Bachelors"
	- "RN - Associates"
	- "LPN"
	- "Nursing Student"
license_state: str
	- State that nurse practices
	- "Student"
hospital_id: str
trust: int
is_test: bool
created_at: str - timestamptz
modified_at: str - timestamptz
likes: list[str]


