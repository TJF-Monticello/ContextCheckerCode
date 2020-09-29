Return context entries that meet the following criteria (Starting at "Where" statement):
	
Check for missing entries on General Section on the Recording Info tab:
	Are from a given project and 
	Level Type is NULL or Deposit Type is NULL or Excavated Yes/No is null or
	Deposit Type equals Surface Collection but Level Type is not equal to Not Applicable

Missing Measurements:
	Are from a given project and 
	Context length is null, or Content width is null, or MaxLithoStratigraphicThickness is null or
	Unit Type = Quadrat/Unit and Quadrat length is null or Quadrat width is null

Missing Quadrat ID/Feature Number:
	Are from a given project and 
	Unit Type equals quadrat/unit but QuadratID is blank
	Unit Type equals feature but Feature Number is blank

Missing Excavator Info
	Are from a given project and
	Excavated by is null or Recorded by is null
	Date Opened or Date Closed is null

Missing Context Sample:
	Are from a given project and
	ContextSampleID is null