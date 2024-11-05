# Database Design

## Table: AD_Element
| Column Name | Data Type | PK | FK | Size |
|-------------|-----------|----|----|------|
| AD_Element_ID | int | Yes | No | 10 |
| Name | varchar | No | No | 60 |
| Description | varchar | No | No | 255 |
| Help | varchar | No | No | 2000 |
| ColumnName | varchar | No | No | 40 |
| EntityType | varchar | No | No | 4 |
| AD_Client_ID | int | No | Yes | 10 |
| AD_Org_ID | int | No | Yes | 10 |
| IsActive | char | No | No | 1 |
| Created | timestamp | No | No | 7 |
| CreatedBy | int | No | Yes | 10 |
| Updated | timestamp | No | No | 7 |
| UpdatedBy | int | No | Yes | 10 |

## Table: AD_Registration
| Column Name | Data Type | PK | FK | Size |
|-------------|-----------|----|----|------|
| AD_Registration_ID | int | Yes | No | 10 |
| Name | varchar | No | No | 60 |
| Description | varchar | No | No | 255 |
| Help | varchar | No | No | 2000 |
| AD_Client_ID | int | No | Yes | 10 |
| AD_Org_ID | int | No | Yes | 10 |
| IsActive | char | No | No | 1 |
| Created | timestamp | No | No | 7 |
| CreatedBy | int | No | Yes | 10 |
| Updated | timestamp | No | No | 7 |
| UpdatedBy | int | No | Yes | 10 |

## Table: AD_Tree
| Column Name | Data Type | PK | FK | Size |
|-------------|-----------|----|----|------|
| AD_Tree_ID | int | Yes | No | 10 |
| Name | varchar | No | No | 60 |
| Description | varchar | No | No | 255 |
| Help | varchar | No | No | 2000 |
| AD_Client_ID | int | No | Yes | 10 |
| AD_Org_ID | int | No | Yes | 10 |
| IsActive | char | No | No | 1 |
| Created | timestamp | No | No | 7 |
| CreatedBy | int | No | Yes | 10 |
| Updated | timestamp | No | No | 7 |
| UpdatedBy | int | No | Yes | 10 |

## Table: R_Category
| Column Name | Data Type | PK | FK | Size |
|-------------|-----------|----|----|------|
| R_Category_ID | int | Yes | No | 10 |
| Name | varchar | No | No | 60 |
| Description | varchar | No | No | 255 |
| Help | varchar | No | No | 2000 |
| AD_Client_ID | int | No | Yes | 10 |
| AD_Org_ID | int | No | Yes | 10 |
| IsActive | char | No | No | 1 |
| Created | timestamp | No | No | 7 |
| CreatedBy | int | No | Yes | 10 |
| Updated | timestamp | No | No | 7 |
| UpdatedBy | int | No | Yes | 10 |

## Table: GL_Category
| Column Name | Data Type | PK | FK | Size |
|-------------|-----------|----|----|------|
| GL_Category_ID | int | Yes | No | 10 |
| Name | varchar | No | No | 60 |
| Description | varchar | No | No | 255 |
| Help | varchar | No | No | 2000 |
| AD_Client_ID | int | No | Yes | 10 |
| AD_Org_ID | int | No | Yes | 10 |
| IsActive | char | No | No | 1 |
| Created | timestamp | No | No | 7 |
| CreatedBy | int | No | Yes | 10 |
| Updated | timestamp | No | No | 7 |
| UpdatedBy | int | No | Yes | 10 |

## Table: K_Category
| Column Name | Data Type | PK | FK | Size |
|-------------|-----------|----|----|------|
| K_Category_ID | int | Yes | No | 10 |
| Name | varchar | No | No | 60 |
| Description | varchar | No | No | 255 |
| Help | varchar | No | No | 2000 |
| AD_Client_ID | int | No | Yes | 10 |
| AD_Org_ID | int | No | Yes | 10 |
| IsActive | char | No | No | 1 |
| Created | timestamp | No | No | 7 |
| CreatedBy | int | No | Yes | 10 |
| Updated | timestamp | No | No | 7 |
| UpdatedBy | int | No | Yes | 10 |

## Table: C_ValidCombination
| Column Name | Data Type | PK | FK | Size |
|-------------|-----------|----|----|------|
| C_ValidCombination_ID | int | Yes | No | 10 |
| Name | varchar | No | No | 60 |
| Description | varchar | No | No | 255 |
| Help | varchar | No | No | 2000 |
| AD_Client_ID | int | No | Yes | 10 |
| AD_Org_ID | int | No | Yes | 10 |
| IsActive | char | No | No | 1 |
| Created | timestamp | No | No | 7 |
| CreatedBy | int | No | Yes | 10 |
| Updated | timestamp | No | No | 7 |
| UpdatedBy | int | No | Yes | 10 |

## Table: C_Phase
| Column Name | Data Type | PK | FK | Size |
|-------------|-----------|----|----|------|
| C_Phase_ID | int | Yes | No | 10 |
| Name | varchar | No | No | 60 |
| Description | varchar | No | No | 255 |
| Help | varchar | No | No | 2000 |
| AD_Client_ID | int | No | Yes | 10 |
| AD_Org_ID | int | No | Yes | 10 |
| IsActive | char | No | No | 1 |
| Created | timestamp | No | No | 7 |
| CreatedBy | int | No | Yes | 10 |
| Updated | timestamp | No | No | 7 |
| UpdatedBy | int | No | Yes | 10 |

## Table: C_Task
| Column Name | Data Type | PK | FK | Size |
|-------------|-----------|----|----|------|
| C_Task_ID | int | Yes | No | 10 |
| Name | varchar | No | No | 60 |
| Description | varchar | No | No | 255 |
| Help | varchar | No | No | 2000 |
| AD_Client_ID | int | No | Yes | 10 |
| AD_Org_ID | int | No | Yes | 10 |
| IsActive | char | No | No | 1 |
| Created | timestamp | No | No | 7 |
| CreatedBy | int | No | Yes | 10 |
| Updated | timestamp | No | No | 7 |
| UpdatedBy | int | No | Yes | 10 |
