# intellectual-sign-language-
british sign language 

    "CampaignId": "2d5741fe-8dde-4210-8d6b-4b324d60f7c1",
    "StartTimeUtc": "2017-01-01T00:00:00Z",
    "EndTimeUtc": "2028-01-01T00:00:00Z",
    "GovernedChannelType": 0,
    "NominationScheme": {
        "Type": 0,
        "PercentageNumerator": 1,
        "PercentageDenominator": 100,
        "NominationPeriod": {
            "Type": 0,
            "IntervalSeconds": 2592000
        },
        "CooldownPeriod": {
            "Type": 0,
            "IntervalSeconds": 7776000
        }
    },
    "SurveyTemplate": {
        "Type": 0,
        "ActivationEvent": {
            "Type": 1,
            "Sequence": [{
                    "Type": 0,
                    "Activity": "InstallTimeSatisfy",
                    "IsAggregate": true,
                    "Count": 1
                },
                {
                    "Type": 0,
                    "Activity": "AppUsageTime",
                    "IsAggregate": true,
                    "Count": 120
                },
                {
                    "Type": 0,
                    "Activity": "AppResume",
                    "IsAggregate": false,
                    "Count": 1
                }
            ]
        }
    }
}]
