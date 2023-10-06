<!-- markdownlint-disable -->

# API Overview

## Modules

- [`classifier`](./classifier.md#module-classifier)
- [`classifier.classifier`](./classifier.classifier.md#module-classifierclassifier)
- [`classifier.predict`](./classifier.predict.md#module-classifierpredict)
- [`common`](./common.md#module-common)
- [`common.Singleton`](./common.Singleton.md#module-commonsingleton)
- [`common.enum`](./common.enum.md#module-commonenum)
- [`common.error_handler`](./common.error_handler.md#module-commonerror_handler)
- [`common.logger`](./common.logger.md#module-commonlogger)
- [`common.testing_list`](./common.testing_list.md#module-commontesting_list)
- [`common.types_list`](./common.types_list.md#module-commontypes_list)
- [`common.util`](./common.util.md#module-commonutil)
- [`common.util_parsing`](./common.util_parsing.md#module-commonutil_parsing)
- [`model`](./model.md#module-model)
- [`model.entity`](./model.entity.md#module-modelentity)
- [`model.identifier`](./model.identifier.md#module-modelidentifier)
- [`model.input`](./model.input.md#module-modelinput)
- [`model.issue`](./model.issue.md#module-modelissue)
- [`model.project`](./model.project.md#module-modelproject)
- [`nlp`](./nlp.md#module-nlp)
- [`nlp.pos_tag`](./nlp.pos_tag.md#module-nlppos_tag)
- [`nlp.pos_tagger_stanford`](./nlp.pos_tagger_stanford.md#module-nlppos_tagger_stanford)
- [`nlp.related_terms`](./nlp.related_terms.md#module-nlprelated_terms)
- [`nlp.splitter`](./nlp.splitter.md#module-nlpsplitter)
- [`nlp.term_list`](./nlp.term_list.md#module-nlpterm_list)
- [`nlp.term_property`](./nlp.term_property.md#module-nlpterm_property)
- [`rule`](./rule.md#module-rule)
- [`rule.linguistic_antipattern`](./rule.linguistic_antipattern.md#module-rulelinguistic_antipattern)
- [`rule.linguistic_antipattern.attribute_name_type_opposite`](./rule.linguistic_antipattern.attribute_name_type_opposite.md#module-rulelinguistic_antipatternattribute_name_type_opposite)
- [`rule.linguistic_antipattern.attribute_signature_comment_opposite`](./rule.linguistic_antipattern.attribute_signature_comment_opposite.md#module-rulelinguistic_antipatternattribute_signature_comment_opposite)
- [`rule.linguistic_antipattern.contains_only_special_characters`](./rule.linguistic_antipattern.contains_only_special_characters.md#module-rulelinguistic_antipatterncontains_only_special_characters)
- [`rule.linguistic_antipattern.expecting_not_getting_collection`](./rule.linguistic_antipattern.expecting_not_getting_collection.md#module-rulelinguistic_antipatternexpecting_not_getting_collection)
- [`rule.linguistic_antipattern.expecting_not_getting_single`](./rule.linguistic_antipattern.expecting_not_getting_single.md#module-rulelinguistic_antipatternexpecting_not_getting_single)
- [`rule.linguistic_antipattern.get_more_than_accessor`](./rule.linguistic_antipattern.get_more_than_accessor.md#module-rulelinguistic_antipatternget_more_than_accessor)
- [`rule.linguistic_antipattern.get_no_return`](./rule.linguistic_antipattern.get_no_return.md#module-rulelinguistic_antipatternget_no_return)
- [`rule.linguistic_antipattern.is_no_return_bool`](./rule.linguistic_antipattern.is_no_return_bool.md#module-rulelinguistic_antipatternis_no_return_bool)
- [`rule.linguistic_antipattern.method_name_return_opposite`](./rule.linguistic_antipattern.method_name_return_opposite.md#module-rulelinguistic_antipatternmethod_name_return_opposite)
- [`rule.linguistic_antipattern.method_signature_comment_opposite`](./rule.linguistic_antipattern.method_signature_comment_opposite.md#module-rulelinguistic_antipatternmethod_signature_comment_opposite)
- [`rule.linguistic_antipattern.name_suggest_boolean_type_not`](./rule.linguistic_antipattern.name_suggest_boolean_type_not.md#module-rulelinguistic_antipatternname_suggest_boolean_type_not)
- [`rule.linguistic_antipattern.not_answered_question`](./rule.linguistic_antipattern.not_answered_question.md#module-rulelinguistic_antipatternnot_answered_question)
- [`rule.linguistic_antipattern.not_implemented_condition`](./rule.linguistic_antipattern.not_implemented_condition.md#module-rulelinguistic_antipatternnot_implemented_condition)
- [`rule.linguistic_antipattern.says_many_contains_one`](./rule.linguistic_antipattern.says_many_contains_one.md#module-rulelinguistic_antipatternsays_many_contains_one)
- [`rule.linguistic_antipattern.says_one_contains_many`](./rule.linguistic_antipattern.says_one_contains_many.md#module-rulelinguistic_antipatternsays_one_contains_many)
- [`rule.linguistic_antipattern.set_returns`](./rule.linguistic_antipattern.set_returns.md#module-rulelinguistic_antipatternset_returns)
- [`rule.linguistic_antipattern.starts_with_special_character`](./rule.linguistic_antipattern.starts_with_special_character.md#module-rulelinguistic_antipatternstarts_with_special_character)
- [`rule.linguistic_antipattern.test_annotation_setup`](./rule.linguistic_antipattern.test_annotation_setup.md#module-rulelinguistic_antipatterntest_annotation_setup)
- [`rule.linguistic_antipattern.test_annotation_teardown`](./rule.linguistic_antipattern.test_annotation_teardown.md#module-rulelinguistic_antipatterntest_annotation_teardown)
- [`rule.linguistic_antipattern.test_annotation_test`](./rule.linguistic_antipattern.test_annotation_test.md#module-rulelinguistic_antipatterntest_annotation_test)
- [`rule.linguistic_antipattern.test_missing_null_check`](./rule.linguistic_antipattern.test_missing_null_check.md#module-rulelinguistic_antipatterntest_missing_null_check)
- [`rule.linguistic_antipattern.test_nonverb_starting`](./rule.linguistic_antipattern.test_nonverb_starting.md#module-rulelinguistic_antipatterntest_nonverb_starting)
- [`rule.linguistic_antipattern.transform_not_return`](./rule.linguistic_antipattern.transform_not_return.md#module-rulelinguistic_antipatterntransform_not_return)
- [`rule.linguistic_antipattern.validate_not_confirm`](./rule.linguistic_antipattern.validate_not_confirm.md#module-rulelinguistic_antipatternvalidate_not_confirm)
- [`service`](./service.md#module-service)
- [`service.factory`](./service.factory.md#module-servicefactory)
- [`service.parser`](./service.parser.md#module-serviceparser)

## Classes

- [`classifier.Classifier`](./classifier.classifier.md#class-classifier): Class for text classification using a pre-trained model.
- [`predict.Predicter`](./classifier.predict.md#class-predicter)
- [`Singleton.Singleton`](./common.Singleton.md#class-singleton)
- [`enum.FileType`](./common.enum.md#class-filetype): Enumeration of file types.
- [`enum.GreetIssueType`](./common.enum.md#class-greetissuetype): An enumeration.
- [`enum.IdentifierType`](./common.enum.md#class-identifiertype): Enumeration of identifier types.
- [`enum.LanguageType`](./common.enum.md#class-languagetype): Enumeration of programming languages.
- [`error_handler.ErrorSeverity`](./common.error_handler.md#class-errorseverity): Enumeration representing error severity levels.
- [`testing_list.TestingPackage`](./common.testing_list.md#class-testingpackage)
- [`entity.Entity`](./model.entity.md#class-entity)
- [`identifier.Attribute`](./model.identifier.md#class-attribute): Represents an attribute within a class.
- [`identifier.Class`](./model.identifier.md#class-class): Represents a class in the source code.
- [`identifier.Method`](./model.identifier.md#class-method): Represents a method within a class.
- [`identifier.Parameter`](./model.identifier.md#class-parameter): Represents a parameter passed to a method.
- [`identifier.Property`](./model.identifier.md#class-property): Represents a property within a class.
- [`identifier.Variable`](./model.identifier.md#class-variable): Represents a variable within a method.
- [`input.Input`](./model.input.md#class-input)
- [`issue.Issue`](./model.issue.md#class-issue)
- [`project.ConfigCustomFileType`](./model.project.md#class-configcustomfiletype): An enumeration.
- [`project.Project`](./model.project.md#class-project)
- [`pos_tag.POSType`](./nlp.pos_tag.md#class-postype): An enumeration.
- [`pos_tagger_stanford.POSTaggerStanford`](./nlp.pos_tagger_stanford.md#class-postaggerstanford): Singleton class for interacting with the Stanford Part-of-Speech Tagger.
- [`splitter.Splitter`](./nlp.splitter.md#class-splitter): Singleton class for splitting text.
- [`attribute_name_type_opposite.AttributeNameTypeOpposite`](./rule.linguistic_antipattern.attribute_name_type_opposite.md#class-attributenametypeopposite)
- [`attribute_signature_comment_opposite.AttributeSignatureCommentOpposite`](./rule.linguistic_antipattern.attribute_signature_comment_opposite.md#class-attributesignaturecommentopposite)
- [`contains_only_special_characters.ContainsOnlySpecialCharacters`](./rule.linguistic_antipattern.contains_only_special_characters.md#class-containsonlyspecialcharacters)
- [`expecting_not_getting_collection.ExpectingNotGettingCollection`](./rule.linguistic_antipattern.expecting_not_getting_collection.md#class-expectingnotgettingcollection)
- [`expecting_not_getting_single.ExpectingNotGettingSingle`](./rule.linguistic_antipattern.expecting_not_getting_single.md#class-expectingnotgettingsingle)
- [`get_more_than_accessor.GetMoreThanAccessor`](./rule.linguistic_antipattern.get_more_than_accessor.md#class-getmorethanaccessor)
- [`get_no_return.GetNoReturn`](./rule.linguistic_antipattern.get_no_return.md#class-getnoreturn)
- [`is_no_return_bool.IsNoReturnBool`](./rule.linguistic_antipattern.is_no_return_bool.md#class-isnoreturnbool)
- [`method_name_return_opposite.MethodNameReturnOpposite`](./rule.linguistic_antipattern.method_name_return_opposite.md#class-methodnamereturnopposite)
- [`method_signature_comment_opposite.MethodSignatureCommentOpposite`](./rule.linguistic_antipattern.method_signature_comment_opposite.md#class-methodsignaturecommentopposite)
- [`name_suggest_boolean_type_not.NameSuggestBooleanTypeNot`](./rule.linguistic_antipattern.name_suggest_boolean_type_not.md#class-namesuggestbooleantypenot)
- [`not_answered_question.NotAnsweredQuestion`](./rule.linguistic_antipattern.not_answered_question.md#class-notansweredquestion)
- [`not_implemented_condition.NotImplementedCondition`](./rule.linguistic_antipattern.not_implemented_condition.md#class-notimplementedcondition)
- [`says_many_contains_one.SaysManyContainsOne`](./rule.linguistic_antipattern.says_many_contains_one.md#class-saysmanycontainsone)
- [`says_one_contains_many.SaysOneContainsMany`](./rule.linguistic_antipattern.says_one_contains_many.md#class-saysonecontainsmany)
- [`set_returns.SetReturns`](./rule.linguistic_antipattern.set_returns.md#class-setreturns)
- [`starts_with_special_character.StartsWithSpecialCharacter`](./rule.linguistic_antipattern.starts_with_special_character.md#class-startswithspecialcharacter)
- [`test_annotation_setup.TestAnnotationSetup`](./rule.linguistic_antipattern.test_annotation_setup.md#class-testannotationsetup)
- [`test_annotation_teardown.TestAnnotationTeardown`](./rule.linguistic_antipattern.test_annotation_teardown.md#class-testannotationteardown)
- [`test_annotation_test.TestAnnotationTest`](./rule.linguistic_antipattern.test_annotation_test.md#class-testannotationtest)
- [`test_missing_null_check.TestMissingNullCheck`](./rule.linguistic_antipattern.test_missing_null_check.md#class-testmissingnullcheck)
- [`test_nonverb_starting.TestNonVerbStarting`](./rule.linguistic_antipattern.test_nonverb_starting.md#class-testnonverbstarting)
- [`transform_not_return.TransformNotReturn`](./rule.linguistic_antipattern.transform_not_return.md#class-transformnotreturn)
- [`validate_not_confirm.ValidateNotConfirm`](./rule.linguistic_antipattern.validate_not_confirm.md#class-validatenotconfirm)
- [`factory.EntityFactory`](./service.factory.md#class-entityfactory): A factory class for constructing Entity objects from source code files.
- [`parser.Parser`](./service.parser.md#class-parser): A utility class for parsing source code files using srcML.
- [`parser.PythonParser`](./service.parser.md#class-pythonparser)
- [`parser.Structures`](./service.parser.md#class-structures): An enumeration.

## Functions

- [`error_handler.handle_error`](./common.error_handler.md#function-handle_error): Handle and log error messages with specified severity.
- [`logger.setup_logger`](./common.logger.md#function-setup_logger): Set up a logger with the specified configuration.
- [`testing_list.get_null_check_test_method`](./common.testing_list.md#function-get_null_check_test_method): Get null check test methods for a specific programming language.
- [`testing_list.get_test_method_annotations`](./common.testing_list.md#function-get_test_method_annotations): Get test method annotations for a specific programming language.
- [`testing_list.get_testing_packages`](./common.testing_list.md#function-get_testing_packages): Get testing packages for a specific programming language.
- [`types_list.get_bool_types`](./common.types_list.md#function-get_bool_types): Get boolean data types for a specific programming language.
- [`types_list.get_collection_types`](./common.types_list.md#function-get_collection_types): Get collection data types for a specific programming language.
- [`types_list.get_numeric_types`](./common.types_list.md#function-get_numeric_types): Get numeric data types for a specific programming language.
- [`types_list.get_primitive_types`](./common.types_list.md#function-get_primitive_types): Get primitive data types for a specific programming language.
- [`util.get_config_setting`](./common.util.md#function-get_config_setting): Retrieve a specific configuration value from a configuration file.
- [`util.get_file_name`](./common.util.md#function-get_file_name): Extract the file name from a given file path.
- [`util.get_supported_file_extensions`](./common.util.md#function-get_supported_file_extensions): Get a list of supported file extensions.
- [`util.read_input`](./common.util.md#function-read_input): Read and process input data from a CSV file.
- [`util.remove_list_nestings`](./common.util.md#function-remove_list_nestings): Flatten a nested list, removing all levels of nesting.
- [`util_parsing.get_all_class_fields`](./common.util_parsing.md#function-get_all_class_fields): Get all class fields (attributes, method variables, and method parameters) in a given entity class.
- [`util_parsing.get_all_conditional_statements`](./common.util_parsing.md#function-get_all_conditional_statements)
- [`util_parsing.get_all_exception_throws`](./common.util_parsing.md#function-get_all_exception_throws)
- [`util_parsing.get_all_function_calls`](./common.util_parsing.md#function-get_all_function_calls)
- [`util_parsing.get_all_items_in_class`](./common.util_parsing.md#function-get_all_items_in_class): Get all items (class, attributes, methods, variables, and parameters) in a given entity class.
- [`util_parsing.get_all_return_statements`](./common.util_parsing.md#function-get_all_return_statements)
- [`util_parsing.get_class_attribute_names`](./common.util_parsing.md#function-get_class_attribute_names): Get the names of attributes for a given entity class.
- [`util_parsing.is_boolean_type`](./common.util_parsing.md#function-is_boolean_type): Check if an identifier has a boolean data type in the context of a given entity.
- [`util_parsing.is_test_method`](./common.util_parsing.md#function-is_test_method): Check if an identifier is a test method within a given project and entity.
- [`pos_tag.generate_tag`](./nlp.pos_tag.md#function-generate_tag): Generate a part-of-speech (POS) tag for a given term in a specific project.
- [`pos_tag.get_tag_text`](./nlp.pos_tag.md#function-get_tag_text): Returns the part of speech type of a given tag.
- [`related_terms.are_antonyms`](./nlp.related_terms.md#function-are_antonyms): Check if two terms are antonyms.
- [`related_terms.clean_text`](./nlp.related_terms.md#function-clean_text): Clean and tokenize text.
- [`related_terms.get_synonyms`](./nlp.related_terms.md#function-get_synonyms): Get synonyms for a term based on its part-of-speech (POS).
- [`related_terms.remove_stopwords`](./nlp.related_terms.md#function-remove_stopwords): Remove stopwords from a list of terms.
- [`term_list.get_boolean_terms`](./nlp.term_list.md#function-get_boolean_terms): Get boolean terms for a project.
- [`term_list.get_conditional_terms`](./nlp.term_list.md#function-get_conditional_terms): Get conditional terms for a project.
- [`term_list.get_get_terms`](./nlp.term_list.md#function-get_get_terms): Get terms related to retrieving data for a project.
- [`term_list.get_plural_terms`](./nlp.term_list.md#function-get_plural_terms): Get plural terms for a project.
- [`term_list.get_pos_terms`](./nlp.term_list.md#function-get_pos_terms): Get the part-of-speech (POS) terms for a project.
- [`term_list.get_set_terms`](./nlp.term_list.md#function-get_set_terms): Get terms related to setting data for a project.
- [`term_list.get_splitter_terms`](./nlp.term_list.md#function-get_splitter_terms): Get the splitter terms for a project.
- [`term_list.get_transform_terms_inner`](./nlp.term_list.md#function-get_transform_terms_inner): Get terms used within transformations for a project.
- [`term_list.get_transform_terms_staring`](./nlp.term_list.md#function-get_transform_terms_staring): Get terms used to start transformations for a project.
- [`term_list.get_validate_terms`](./nlp.term_list.md#function-get_validate_terms): Get validation terms for a project.
- [`term_property.is_plural`](./nlp.term_property.md#function-is_plural): Check if a term is in plural form.
- [`term_property.is_singular`](./nlp.term_property.md#function-is_singular): Check if a term is in singular form.


---

_This file was automatically generated via [lazydocs](https://github.com/ml-tooling/lazydocs)._
