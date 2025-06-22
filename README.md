# Amazon-Prduct-Review-Analysis

= Table.TransformColumnTypes(#"Promoted Headers",{{"Sheet 1: Summary Dashboard Data", type any}, {"Column2", type any}, {"Column3", type any}, {"Column4", type any}, {"Column5", type any}, {"Column6", type any}, {"Column7", type any}})

= Table.TransformColumnTypes(#"Promoted Headers",{{"Metric", type text}, {"Value", type any}})

= Table.TransformColumnTypes(#"Promoted Headers",{{"Category", type text}, {"Product Count", Int64.Type}, {"Avg Discount %", type number}, {"Avg Discount %_1", type number}, {"Avg Discounted Price (₹)", Int64.Type}, {"Total Reviews", Int64.Type}, {"Total Revenue (₹)", Int64.Type}})

= Table.TransformColumnTypes(#"Promoted Headers",{{"Rating", type any}, {"Product Count", Int64.Type}})

= Table.TransformColumnTypes(#"Promoted Headers",{{"Price Range", type text}, {"Product Count", Int64.Type}})

= Table.TransformColumnTypes(#"Promoted Headers",{{"Product Name", type text}, {"Avg Rating", type number}, {"Total Reviews", Int64.Type}, {"Total Reviews_1", Int64.Type}})

= Table.TransformColumnTypes(#"Promoted Headers",{{"Discount Range", type text}, {"Avg Rating", type number}})
