###util.ts needs to go away.  There are multple functions.  some are duplicates of existing and some can be split into own files.  The functions that can remain have been placed in this folder as separaate files.

isNullUndefinedOrEmptyString ->  this does the same thing as hasValue
isNullUndefinedEmptyOrZero -> this should call hasValue then check if 0
isAnyEmpty -> this should call hasValue on each item
isAnyNullOrUndefined -> not used and should go away
isAllNullOrUndefined -> should call hasValue for each
isNullOrUndefined -> can be replaced with hasValue
isNullUndefinedEmptyOrWhiteSpace -> also replaced with hasValue