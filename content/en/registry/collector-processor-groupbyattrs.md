---
title: Group by Attributes processor
registryType: processor
isThirdParty: false
language: collector
tags:
    - go
    - processor
    - collector
repo: https://github.com/open-telemetry/opentelemetry-collector-contrib/tree/main/processor/groupbyattrsprocessor
license: Apache 2.0
description: This processor re-associates spans, log records and metric datapoints to a Resource that matches with the specified attributes. As a result, all spans, log records or metric datapoints with the same values for the specified attributes are "grouped" under the same Resource.
authors: OpenTelemetry Authors
otVersion: latest
---
