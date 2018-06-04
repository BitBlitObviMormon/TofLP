# Practicum Project

## [Family](javascript:openTab('FamilyTab'))
> Place quotes here
{: .tab }
{: #FamilyTab }

## [Agency](javascript:openTab('AgencyTab'))
> Place quotes here
{: .tab }
{: #AgencyTab }

## [Atonement](javascript:openTab('AtonementTab'))
> Place quotes here
{: .tab }
{: #AtonementTab }

## [Addiction](javascript:openTab('AddictionTab'))
> Place quotes here
{: .tab }
{: #AddictionTab }

## [Temple](javascript:openTab('TempleTab'))
> Place quotes here
{: .tab }
{: #TempleTab }

## [Family History](javascript:openTab('FamilyHistoryTab'))
> Place quotes here
{: .tab }
{: #FamilyHistoryTab }

## [Missionary Work](javascript:openTab('MissionaryWorkTab'))
> Place quotes here
{: .tab }
{: #MissionaryWorkTab }

## [Education](javascript:openTab('EducationTab'))
> Place quotes here
{: .tab }
{: #EducationTab }

<script>
closeTabs();
function closeTabs() {
	var i;
	var x = document.getElementsByClassName("tab");
	for (i = 0; i < x.length; i++) {
		x[i].style.display = "none";
	}
}

function openTab(tabName) {
	closeTabs();
	document.getElementById(tabName).style.display = "block";
}
</script>